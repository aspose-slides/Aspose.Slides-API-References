---
title: OperatingSystem
second_title: مرجع API Aspose.Slides برای C++
description: "نمایشگر یک سیستم‌عامل خاص است و اطلاعاتی درباره آن فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را در پشته یا با استفاده از operator new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا خواهد شد. همیشه این کلاس را در اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 1171
url: /fa/system/operatingsystem/
---
## OperatingSystem کلاس

نمایشگر یک سیستم‌عامل خاص است و اطلاعاتی درباره آن فراهم می‌کند. شیءهای این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../makeobject/) اختصاص یابند. هرگز نمونه‌ای از این نوع را در پشته یا با استفاده از operator new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا خواهد شد. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class OperatingSystem
```

## متدها

| متد | توضیح |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | شناسه پلتفرم سیستم‌عامل نمایان‌شده توسط شیء فعلی را بر می‌گرداند. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | نام سرویس پک سیستم‌عامل نمایان‌شده توسط شیء فعلی را بر می‌گرداند. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | یک ارجاع ثابت به شیء [Version](../version/) که نشان‌دهنده نسخه سیستم‌عامل نمایان‌شده توسط شیء فعلی است را بر می‌گرداند. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | نمایش رشته‌ای از نسخهٔ سیستم‌عامل نمایان‌شده توسط شیء فعلی را بر می‌گرداند. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | نشان می‌دهد که برنامهٔ فعلی بر روی FreeBSD اجرا می‌شود یا نه. |
| static **bool** [IsLinux](./islinux/)() | نشان می‌دهد که برنامهٔ فعلی بر روی Linux اجرا می‌شود یا نه. |
| static **bool** [IsMacOS](./ismacos/)() | نشان می‌دهد که برنامهٔ فعلی بر روی MacOS اجرا می‌شود یا نه. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | نشان می‌دهد که برنامهٔ فعلی بر روی پلتفرم مشخص شده اجرا می‌شود یا نه. |
| static **bool** [IsWindows](./iswindows/)() | نشان می‌دهد که برنامهٔ فعلی بر روی [Windows](../../system.windows/) اجرا می‌شود یا نه. |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | یک نمونه را می‌سازد که نمایانگر یک سیستم‌عامل مشخص به عنوان شناسه پلتفرم خاص و نسخه است. |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | یک نمونه را می‌سازد که نمایانگر یک سیستم‌عامل مشخص به عنوان شناسه پلتفرم، نسخه و سرویس پک است. |
| [String](../string/) [ToString](./tostring/)() const | نمایش رشته‌ای از نسخهٔ سیستم‌عامل نمایان‌شده توسط شیء فعلی را بر می‌گرداند. |

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)