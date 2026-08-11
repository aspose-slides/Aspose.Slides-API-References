---
title: BlobManagementOptions
second_title: Aspose.Slides برای C++ مرجع API
description: گزینه‌هایی که می‌توان برای مدیریت قوانین پردازش BLOB و سایر تنظیمات BLOB استفاده کرد، را نمایش می‌دهد.
type: docs
weight: 196
url: /fa/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions کلاس

گزینه‌هایی را که می‌توان برای مدیریت قوانین پردازش BLOB و سایر تنظیمات BLOB استفاده کرد، نمایان می‌کند.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## متدها

| Method | Description |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | گزینه‌های پیش‌فرض مدیریت blob را ایجاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنایی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع value را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | این ویژگی تعیین می‌کند که آیا فایل‌های موقت می‌توانند در هنگام کار با BLOBها ایجاد شوند یا نه، که مصرف حافظه را به شدت کاهش می‌دهد ولی نیاز به مجوزهای ایجاد فایل دارد. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | حداکثر اندازهٔ کلی (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. به‌طور پیش‌فرض، تمام BLOBها در حافظه بارگذاری می‌شوند؛ فقط وقتی این سقف رسیده باشد مکانیزم‌های جایگزین (مانند فایل‌های موقت) به کار گرفته می‌شوند. نگهداری BLOBها در حافظه عملکرد را بیشینه می‌کند اما می‌تواند منجر به مصرف بالای حافظه شود. از این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس [Presentation](../presentation/) می‌تواند مالک منبع - فایل یا جریان - در طول عمر نمونه باشد یا نه. اگر نمونه مالک باشد، منبع را قفل می‌کند. این کار به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) نمی‌تواند در طول عمر نمونه [Presentation](../presentation/) تغییر کند. |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض، دایرکتوری موقت [System](../../system/) استفاده خواهد شد. فرآیند میزبانی باید مجوزهای ایجاد فایل و پوشه در آن مسیر را داشته باشد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. هش‌گذاری اشیاء سفارشی را امکان‌پذیر می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت lock() در C# را اجرا می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع value را با nullptr از طریق مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | این ویژگی تعیین می‌کند که آیا فایل‌های موقت می‌توانند در هنگام کار با BLOBها ایجاد شوند یا نه، که مصرف حافظه را به شدت کاهش می‌دهد ولی نیاز به مجوزهای ایجاد فایل دارد. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | حداکثر اندازهٔ کلی (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. به‌طور پیش‌فرض، تمام BLOBها در حافظه بارگذاری می‌شوند؛ فقط وقتی این سقف رسیده باشد مکانیزم‌های جایگزین (مانند فایل‌های موقت) به کار گرفته می‌شوند. نگهداری BLOBها در حافظه عملکرد را بیشینه می‌کند اما می‌تواند منجر به مصرف بالای حافظه شود. از این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس [Presentation](../presentation/) می‌تواند مالک منبع - فایل یا جریان - در طول عمر نمونه باشد یا نه. اگر نمونه مالک باشد، منبع را قفل می‌کند. این کار به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) نمی‌تواند در طول عمر نمونه [Presentation](../presentation/) تغییر کند. |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض، دایرکتوری موقت [System](../../system/) استفاده خواهد شد. فرآیند میزبانی باید مجوزهای ایجاد فایل و پوشه در آن مسیر را داشته باشد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش مرجع مشترک را افزایش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ به‌جای آن از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به طور مستقیم فراخوانی شود؛ به‌جای آن از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را می‌دهد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری عبارت lock() در C# را اجرا می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارش مرجع ضعیف را افزایش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ به‌جای آن از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارش مرجع ضعیف را کاهش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ به‌جای آن از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IBlobManagementOptions](../iblobmanagementoptions/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)