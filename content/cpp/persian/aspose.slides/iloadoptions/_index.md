---
title: ILoadOptions
second_title: Aspose.Slides برای مرجع API C++
description: به شما امکان می‌دهد هنگام بارگذاری یک ارائه، گزینه‌های اضافی (مانند قالب یا قلم پیش‌فرض) را مشخص کنید.
type: docs
weight: 2796
url: /fa/aspose.slides/iloadoptions/
---
## ILoadOptions کلاس

به امکان تعیین گزینه‌های اضافی (مانند قالب یا قلم پیش‌فرض) هنگام بارگذاری ارائه اجازه می‌دهد.

```cpp
class ILoadOptions : public virtual System::Object
```

## متدها

| متد | توضیحات |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | نمایش‌دهنده گزینه‌هایی است که می‌توان برای مدیریت رفتار مدیریت Binary Large Objects (BLOBs) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOBs در حافظه. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای یک محیط یا نیازهای خاص در نظر گرفته شده‌اند. |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | قلم آسیایی را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | قلم عادی را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | قلم Symbol را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | زبان پیش‌فرض برای متن ارائه را برمی‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | تعیین می‌کند آیا [Aspose.Slides](../) تمام اشیاء باینری تعبیه‌شده را هنگام بارگذاری ارائه حذف می‌کند یا نه. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با سایر ارائه‌ها به اشتراک گذاشته نمی‌شوند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | توکن برای نظارت بر درخواست‌های قطع. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | قالب ارائه‌ای که باید بارگذاری شود را برمی‌گرداند. [Slides::LoadFormat](../loadformat/) را می‌خواند. |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | این ویژگی تنها زمانی معنی دارد که فایل ارائه با رمز عبور محافظت شده باشد. مقدار true به این معناست که فقط ویژگی‌های سند باید از یک فایل ارائه رمزگذاری شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به این معناست که کل ارائه رمزگذاری شده باید با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند قابل بارگذاری نیستند و استثنایی پرتاب می‌شود. **bool** را می‌خواند. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | رمز عبور را دریافت می‌کند. [System::String](../../system/string/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | رابط بازخوانی را که بارگذاری منابع خارجی را مدیریت می‌کند، برمی‌گرداند. [IResourceLoadingCallback](../iresourceloadingcallback/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | نمایش‌دهنده گزینه‌هایی است که می‌توان برای تعیین رفتار اضافی spreadsheets استفاده کرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | شیئی را برمی‌گرداند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد که آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌خواند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | نمایش‌دهنده گزینه‌هایی است که می‌توان برای مدیریت رفتار مدیریت Binary Large Objects (BLOBs) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOBs در حافظه. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای یک محیط یا نیازهای خاص در نظر گرفته شده‌اند. |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | قلم آسیایی را که در صورت عدم یافتن قلم منبع استفاده می‌شود تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | قلم عادی را که در صورت عدم یافتن قلم منبع استفاده می‌شود تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | قلم Symbol را که در صورت عدم یافتن قلم منبع استفاده می‌شود تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | زبان پیش‌فرض برای متن ارائه را تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | تعیین می‌کند آیا [Aspose.Slides](../) تمام اشیاء باینری تعبیه‌شده را هنگام بارگذاری ارائه حذف می‌کند یا نه. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با سایر ارائه‌ها به اشتراک گذاشته نمی‌شوند. |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | توکن برای نظارت بر درخواست‌های قطع. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | قالب ارائه‌ای که باید بارگذاری شود را تنظیم می‌کند. [Slides::LoadFormat](../loadformat/) را می‌نویسد. |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | این ویژگی تنها زمانی معنی دارد که فایل ارائه با رمز عبور محافظت شده باشد. مقدار true به این معناست که فقط ویژگی‌های سند باید از یک فایل ارائه رمزگذاری شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به این معناست که کل ارائه رمزگذاری شده باید با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند قابل بارگذاری نیستند و استثنایی پرتاب می‌شود. **bool** را می‌نویسد. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | رمز عبور را تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | رابط بازخوانی را که بارگذاری منابع خارجی را مدیریت می‌کند تنظیم می‌کند. [IResourceLoadingCallback](../iresourceloadingcallback/) را می‌نویسد. |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | نمایش‌دهنده گزینه‌هایی است که می‌توان برای تعیین رفتار اضافی spreadsheets استفاده کرد. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | شیئی را تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد که آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌نویسد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی عمومی را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## همچنین

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)