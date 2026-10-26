---
title: IBlobManagementOptions
second_title: Aspose.Slides برای C++ مرجع API
description: یک Binary Large Object (BLOB) دادهٔ باینری است که به‌صورت یک واحد ذخیره می‌شود - یعنی BLOB می‌تواند خود یک فایل صوتی، ویدئویی یا ارائه باشد. برای بهینه‌سازی مصرف حافظه هنگام کار با BLOBها از تکنیک‌های مختلفی استفاده می‌شود - چه این داده‌ها از پیش در ارائه ذخیره شده باشند و چه بعدها به‌صورت برنامه‌ای اضافه شوند. با استفاده از IBlobManagementOptions می‌توانید جنبه‌های مختلف رفتار مربوط به مدیریت BLOBها را برای طول عمر نمونهٔ IPresentation تغییر دهید.
type: docs
weight: 1535
url: /fa/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions کلاس

یک Binary Large Object (BLOB) دادهٔ باینری است که به‌صورت یک واحد ذخیره می‌شود - به‌عبارت دیگر BLOB می‌تواند خود یک فایل صوتی، ویدئویی یا ارائه باشد. برای بهینه‌سازی مصرف حافظه هنگام کار با BLOBها از تکنیک‌های مختلفی استفاده می‌شود - چه از قبل در ارائه ذخیره شده باشد و چه به‌صورت برنامه‌نویسی بعداً اضافه شود. با استفاده از [IBlobManagementOptions](./) می‌توانید جوانب مختلف رفتار در مدیریت BLOBها برای طول عمر نمونه [IPresentation](../ipresentation/) را تغییر دهید.

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسهٔ اشیاء با استفاده از semantics C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء از نوع مرجع به سبک C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء از نوع مقدار به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ نقطهٔ شناور به سبک C# که دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ نقطهٔ شناور به سبک C# که دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | این ویژگی تعریف می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طور چشمگیری مصرف حافظه را کاهش می‌دهد اما نیاز به مجوز ایجاد فایل دارد. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | حداکثر اندازهٔ کل (به بایت) را تعریف می‌کند که تمام BLOBها می‌توانند در حافظه اشغال کنند. به‌طور پیش‌فرض، همهٔ BLOBها در حافظه بارگذاری می‌شوند؛ تنها پس از رسیدن به این حد، مکانیزم‌های جایگزین (مانند فایل‌های موقت) به کار گرفته می‌شوند. نگهداری BLOBها در حافظه عملکرد را به حداکثر می‌رساند اما می‌تواند منجر به استفاده بالای حافظه شود. از این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | این ویژگی تعریف می‌کند که آیا یک نمونه از کلاس [Presentation](../presentation/) می‌تواند مالک منبع - فایل یا جریان - در طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع قفل می‌شود. این کمک می‌کند تا مصرف حافظه و عملکرد هنگام کار با BLOBها بهبود یابد، اما منبع (جریان یا فایل) نمی‌تواند در طول مدت زمان نمونهٔ [Presentation](../presentation/) تغییر کند. این یک مثال است: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشهٔ موقت [System](../../system/) استفاده خواهد شد. فرآیند میزبانی باید مجوز ایجاد فایل و پوشه در آنجا را داشته باشد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شی را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# ‎'is'‎. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری statement C# lock(). مستقیماً فراخوانی کنید یا از شی sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | مقایسهٔ اشیاء توسط مرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | مقایسهٔ اشیاء توسط مرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مقدار شیء نوع مقدار با nullptr توسط مرجع. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | این ویژگی تعریف می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طور چشمگیری مصرف حافظه را کاهش می‌دهد اما نیاز به مجوز ایجاد فایل دارد. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | حداکثر اندازهٔ کل (به بایت) را تعریف می‌کند که تمام BLOBها می‌توانند در حافظه اشغال کنند. به‌طور پیش‌فرض، همهٔ BLOBها در حافظه بارگذاری می‌شوند؛ تنها پس از رسیدن به این حد، مکانیزم‌های جایگزین (مانند فایل‌های موقت) به کار گرفته می‌شوند. نگهداری BLOBها در حافظه عملکرد را به حداکثر می‌رساند اما می‌تواند منجر به استفاده بالای حافظه شود. از این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | این ویژگی تعریف می‌کند که آیا یک نمونه از کلاس [Presentation](../presentation/) می‌تواند مالک منبع - فایل یا جریان - در طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع قفل می‌شود. این کمک می‌کند تا مصرف حافظه و عملکرد هنگام کار با BLOBها بهبود یابد، اما منبع (جریان یا فایل) نمی‌تواند در طول مدت زمان نمونهٔ [Presentation](../presentation/) تغییر کند. این یک مثال است: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشهٔ موقت [System](../../system/) استفاده خواهد شد. فرآیند میزبانی باید مجوز ایجاد فایل و پوشه در آنجا را داشته باشد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به اشاره‌گر ضعیف (به جای اشتراک‌گذاری) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی آزادسازی قفل statement C# lock(). مستقیماً فراخوانی کنید یا از شی sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## مشاهده نیز

* Class [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)