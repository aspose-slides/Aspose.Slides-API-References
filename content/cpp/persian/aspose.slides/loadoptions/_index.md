---
title: LoadOptions
second_title: Aspose.Slides برای مرجع API C++
description: به شما امکان می‌دهد گزینه‌های اضافی (مانند قالب یا قلم پیش‌فرض) را هنگام بارگذاری یک ارائه مشخص کنید.
type: docs
weight: 4395
url: /fa/aspose.slides/loadoptions/
---
## LoadOptions کلاس

به‌کارگیری گزینه‌های اضافی (مانند قالب یا قلم پیش‌فرض) هنگام بارگذاری یک ارائه.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | گزینه‌هایی را که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه، نشان می‌دهد. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای یک محیط یا نیازهای خاص در نظر گرفته شده‌اند. |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | فونت آسیایی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازمی‌گرداند. [System::String](../../system/string/) را بخوانید. |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | فونت معمولی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازمی‌گرداند. [System::String](../../system/string/) را بخوانید. |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | فونت Symbol را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازمی‌گرداند. [System::String](../../system/string/) را بخوانید. |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | زبان پیش‌فرض برای متن ارائه را بازمی‌گرداند. [System::String](../../system/string/) را بخوانید. |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | [Aspose.Slides](../) تعیین می‌کند که آیا تمام اشیاء باینری توکار حین بارگذاری ارائه حذف شوند یا نه. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | علامت برای نظارت بر درخواست‌های قطع. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | قالب ارائه‌ای که باید بارگذاری شود را بازمی‌گرداند. [Slides::LoadFormat](../loadformat/) را بخوانید. |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | این ویژگی در صورتی معنی دارد که فایل ارائه با رمز عبور محافظت شده باشد. مقدار true به این معنی است که فقط خصوصیات سند باید از یک فایل ارائه رمزنگاری‌شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به این معنی است که کل ارائه رمزنگاری‌شده باید با استفاده از رمز عبور صحیح بارگذاری شود. اگر ارائه رمزنگاری نشده باشد، همیشه مقدار این ویژگی نادیده گرفته می‌شود. اگر خصوصیات سند یک فایل رمزنگاری‌شده عمومی نباشند و مقدار ویژگی true باشد، خصوصیات سند نمی‌توانند بارگذاری شوند و استثنایی پرتاب می‌شود. Read **bool**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | رمز عبور را دریافت می‌کند. [System::String](../../system/string/) را بخوانید. |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | رابط callback را که مدیریت بارگذاری منابع خارجی را انجام می‌دهد، بازمی‌گرداند. [IResourceLoadingCallback](../iresourceloadingcallback/) را بخوانید. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | گزینه‌های مربوط به صفحه‌گسترده‌ها را دریافت می‌کند. به عنوان مثال، این گزینه‌ها بر محاسبه فرمول‌ها برای نمودارها تأثیر می‌گذارند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | یک شیء را بازمی‌گرداند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه پیدا کند یا متوقف شود. [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌کردن اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
|  [LoadOptions](./loadoptions/)() | گزینه‌های بارگذاری پیش‌فرض جدید را ایجاد می‌کند. |
|  [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | گزینه‌های بارگذاری جدید را ایجاد می‌کند. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌سازی انواع سفارشی را فعال می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع برای شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده‌ی ارجاع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | گزینه‌هایی را که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه، نشان می‌دهد. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای یک محیط یا نیازهای خاص در نظر گرفته شده‌اند. |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | فونت آسیایی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، تنظیم می‌کند. [System::String](../../system/string/) را بنویسید. |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | فونت معمولی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، تنظیم می‌کند. [System::String](../../system/string/) را بنویسید. |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | فونت Symbol را که در صورت عدم یافتن فونت منبع استفاده می‌شود، تنظیم می‌کند. [System::String](../../system/string/) را بنویسید. |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | زبان پیش‌فرض برای متن ارائه را تنظیم می‌کند. [System::String](../../system/string/) را بنویسید. |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | [Aspose.Slides](../) تعیین می‌کند که آیا تمام اشیاء باینری توکار حین بارگذاری ارائه حذف شوند یا نه. |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | علامت برای نظارت بر درخواست‌های قطع. |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | قالب ارائه‌ای که باید بارگذاری شود را تنظیم می‌کند. [Slides::LoadFormat](../loadformat/) را بنویسید. |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | این ویژگی در صورتی معنی دارد که فایل ارائه با رمز عبور محافظت شده باشد. مقدار true به این معنی است که فقط خصوصیات سند باید از یک فایل ارائه رمزنگاری‌شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به این معنی است که کل ارائه رمزنگاری‌شده باید با استفاده از رمز عبور صحیح بارگذاری شود. اگر ارائه رمزنگاری نشده باشد، همیشه مقدار این ویژگی نادیده گرفته می‌شود. اگر خصوصیات سند یک فایل رمزنگاری‌شده عمومی نباشند و مقدار ویژگی true باشد، خصوصیات سند نمی‌توانند بارگذاری شوند و استثنایی پرتاب می‌شود. Write **bool**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | رمز عبور را تنظیم می‌کند. [System::String](../../system/string/) را بنویسید. |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | رابط callback را که مدیریت بارگذاری منابع خارجی را انجام می‌دهد، تنظیم می‌کند. [IResourceLoadingCallback](../iresourceloadingcallback/) را بنویسید. |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | گزینه‌های مربوط به صفحه‌گسترده‌ها را دریافت می‌کند. به عنوان مثال، این گزینه‌ها بر محاسبه فرمول‌ها برای نمودارها تأثیر می‌گذارند. |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | شیئی را تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه یابد یا متوقف شود. [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگمان قالب nام را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده‌ی ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده‌ی ارجاع مشترک را کاهش می‌دهد و مقدار آن را بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده‌ی ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده‌ی ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را خراب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## See Also

* کلاس [ILoadOptions](../iloadoptions/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)