## Backend & AI engineer — self-hosted Python systems

I build software that runs on the client's own server: no monthly SaaS fee, and no data leaving
their infrastructure. Everything below is open source, tested and documented, so you can read the
code before you decide to work with me.

### What I build

- **Chat-based order and booking systems** (Telegram) with an admin API and spreadsheet export
- **Document question-answering with citations** — Arabic and English, running offline
- **Website and uptime monitoring**, including security-header and TLS regressions
- **REST APIs** with authentication, role-based access, database migrations and automated tests

### Projects

| Project | What it does | Tests |
|---|---|--:|
| [**talabflow**](https://github.com/pgun879-alt/talabflow) | Turns chat conversations into tracked orders: reference numbers, a guarded status pipeline, an audit trail, customer notifications through a transactional outbox, a JWT staff API and XLSX/CSV export | 333 |
| [**mustanad**](https://github.com/pgun879-alt/mustanad) | Answers questions about your own documents **with the passage each answer came from**, in Arabic or English, fully offline with no API key. BM25 written from scratch | 238 |
| [**raqib**](https://github.com/pgun879-alt/raqib) | Watches web pages for content, availability and security-posture changes. SSRF guard with DNS pinning, `robots.txt` enforced, one alert per state change instead of one per poll | 298 |

**869 automated tests** across the three, type-checked and linted clean. Each repository documents
its limitations as plainly as its features, and carries a security policy that states what is
deliberately *not* a vulnerability.

**In progress:** [**nexabot**](https://github.com/pgun879-alt/nexabot) — the foundation of an AI assistant
platform (clean architecture, async SQLAlchemy, tested migrations, 143 tests). Not production-ready
yet; its README lists exactly what is still missing.

### How I work

A defined scope before I start · working software you can run yourself · tests that prove it
works · a README complete enough that another developer could take the project over.

### Honest status

These are portfolio projects, not client work. They have **no production users and no uptime
history**, and every repository says so in its own README. What they demonstrate is *how* I
build — including the bugs I found in my own code and wrote tests to keep out.

### Stack

`Python` · `FastAPI` · `SQLAlchemy` · `Alembic` · `SQLite` · `pytest` · `ruff` · `mypy` ·
`Docker` · `Linux`

Working in **Arabic and English** · based in Algeria

---

<div dir="rtl">

## مهندس برمجيات خلفية وذكاء اصطناعي — أنظمة تعمل على خادمك

أبني أنظمة تعمل على خادم العميل نفسه: بلا اشتراك شهري، وبلا خروج البيانات من بنيته التحتية. جميع
المشاريع أدناه مفتوحة المصدر ومُختبَرة وموثَّقة — يمكنك قراءة الشيفرة قبل التعاقد معي.

### ما أبنيه

- أنظمة استقبال الطلبات والحجوزات عبر المحادثة (تيليجرام) مع واجهة إدارة وتصدير إلى Excel
- الإجابة على الأسئلة من مستندات العميل **مع ذكر المصدر**، بالعربية والإنجليزية، دون اتصال
- مراقبة المواقع: تغيّر المحتوى، والتوافر، وتراجع إعدادات الأمان وشهادات TLS
- واجهات REST مع مصادقة وصلاحيات وترحيلات قاعدة بيانات واختبارات آلية

### المشاريع

| المشروع | ما يفعله | الاختبارات |
|---|---|--:|
| [**talabflow**](https://github.com/pgun879-alt/talabflow) | يحوّل المحادثات إلى طلبات مُتابَعة: رقم مرجعي، ومسار حالات محكوم، وسجل تدقيق، وإشعارات تلقائية للعميل، وواجهة إدارة بصلاحيات، وتصدير إلى Excel | ٣٣٣ |
| [**mustanad**](https://github.com/pgun879-alt/mustanad) | يجيب على الأسئلة من مستنداتك **مع المقطع الذي جاءت منه الإجابة**، بالعربية أو الإنجليزية، دون أي مفتاح API | ٢٣٨ |
| [**raqib**](https://github.com/pgun879-alt/raqib) | يراقب صفحات الويب: تغيّر المحتوى، والتوافر، وتراجع الأمان. حارس SSRF، واحترام فعلي لـ robots.txt، وتنبيه واحد لكل تغيّر حالة | ٢٩٨ |

**٨٦٩ اختبارًا آليًا** في المشاريع الثلاثة، وفحص أنواع وتنسيق نظيف بالكامل.

**قيد التطوير:** [**nexabot**](https://github.com/pgun879-alt/nexabot) — أساس منصّة مساعد ذكي (معمارية نظيفة،
SQLAlchemy غير متزامن، ترحيلات مُختبَرة، ١٤٣ اختبارًا). غير جاهز للإنتاج بعد، وملف README فيه يذكر
بدقّة ما ينقصه.

### طريقة عملي

نطاق محدَّد قبل البدء · برنامج يعمل فعليًا يمكنك تشغيله بنفسك · اختبارات تُثبت ذلك · توثيق كافٍ
ليتمكّن مطوّر آخر من استكمال العمل.

### وضوح تام

هذه مشاريع محفظة أعمال وليست أعمال عملاء — **ليس لها مستخدمون في بيئة إنتاج**، وهذا مذكور صراحةً
في كل مستودع. ما تُظهره هو **كيف** أبني.

أعمل بالعربية والإنجليزية · مقيم في الجزائر

</div>
