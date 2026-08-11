---
title: XmlReaderSettings
second_title: Aspose.Slides برای C++ مرجع API
description: "یک مجموعه از ویژگی‌ها را برای پشتیبانی از شیء XmlReader که توسط متد XmlReader::Create ایجاد شده است، مشخص می‌کند."
type: docs
weight: 443
url: /fa/system.xml/xmlreadersettings/
---
## XmlReaderSettings کلاس

یک مجموعه ویژگی‌ها را برای پشتیبانی از شیء [XmlReader](../xmlreader/) که توسط متد [XmlReader::Create](../xmlreader/create/) ایجاد شده است، مشخص می‌کند.

```cpp
class XmlReaderSettings : public System::Object
```

## متدها

| متد | شرح |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | یک کپی از نمونه [XmlReaderSettings](./) ایجاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای کاربردهای داخلی. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | مقدارى را برمی‌گرداند که نشان می‌دهد آیا بررسی کاراکتر انجام شود یا نه. |
| **bool** [get_CloseInput](./get_closeinput/)() | مقدارى را برمی‌گرداند که نشان می‌دهد آیا جریان زیرین یا TextReader هنگام بسته شدن خواننده باید بسته شود یا نه. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | سطح انطباقی که [XmlReader](../xmlreader/) به آن پایبند خواهد شد را برمی‌گرداند. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | مقدارى را برمی‌گرداند که پردازش DTDها را تعیین می‌کند. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | مقدارى را برمی‌گرداند که نشان می‌دهد آیا نظرات نادیده گرفته شوند یا نه. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | مقدارى را برمی‌گرداند که نشان می‌دهد آیا دستورهای پردازش نادیده گرفته شوند یا نه. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | مقدارى را برمی‌گرداند که نشان می‌دهد آیا فضای سفید غیر مهم نادیده گرفته شود یا نه. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | اختلاف شماره خط شیء [XmlReader](../xmlreader/) را برمی‌گرداند. |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | اختلاف موقعیت خط شیء [XmlReader](../xmlreader/) را برمی‌گرداند. |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | مقدارى را برمی‌گرداند که حداکثر تعداد کاراکترهای مجاز در سند حاصل از گسترش موجودیت‌ها را نشان می‌دهد. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | مقدارى را برمی‌گرداند که حداکثر تعداد کاراکترهای مجاز در یک سند XML را نشان می‌دهد. مقدار صفر (0) به معنای عدم وجود محدودیت در اندازه سند XML است. مقدار غیر صفر حداکثر اندازه را برحسب کاراکترها مشخص می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | [XmlNameTable](../xmlnametable/) مورد استفاده برای مقایسه رشته‌های اتمی را برمی‌گرداند. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | مقدارى را برمی‌گرداند که نشان می‌دهد آیا پردازش تعریف نوع سند (DTD) ممنوع شود یا نه. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | XmlSchemaSet مورد استفاده هنگام انجام اعتبارسنجی طرحواره را برمی‌گرداند. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | مقدارى را برمی‌گرداند که تنظیمات اعتبارسنجی طرحواره را نشان می‌دهد. این تنظیم برای اشیاء [XmlReader](../xmlreader/) که طرحواره‌ها را اعتبارسنجی می‌کنند (مقدار [XmlReaderSettings::get_ValidationType](./get_validationtype/) برابر [ValidationType::Schema](../validationtype/)) اعمال می‌شود. |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | مقدارى را برمی‌گرداند که نشان می‌دهد آیا [XmlReader](../xmlreader/) هنگام خواندن اعتبارسنجی یا اختصاص نوع انجام می‌دهد یا نه. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | عملکرد قفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوعی را با nullptr از طریق مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [Reset](./reset/)() | اعضای کلاس تنظیمات را به مقادیر پیش‌فرضشان بازنشانی می‌کند. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | مقدارى را تنظیم می‌کند که نشان می‌دهد آیا بررسی کاراکتر انجام شود یا نه. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | مقدارى را تنظیم می‌کند که نشان می‌دهد آیا جریان زیرین یا TextReader هنگام بسته شدن خواننده باید بسته شود یا نه. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | سطح انطباقی که [XmlReader](../xmlreader/) به آن پایبند خواهد شد را تنظیم می‌کند. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | مقدارى را تنظیم می‌کند که پردازش DTDها را تعیین می‌کند. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | مقدارى را تنظیم می‌کند که نشان می‌دهد آیا نظرات نادیده گرفته شوند یا نه. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | مقدارى را تنظیم می‌کند که نشان می‌دهد آیا دستورهای پردازش نادیده گرفته شوند یا نه. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | مقدارى را تنظیم می‌کند که نشان می‌دهد آیا فضای سفید غیر مهم نادیده گرفته شود یا نه. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | اختلاف شماره خط شیء [XmlReader](../xmlreader/) را تنظیم می‌کند. |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | اختلاف موقعیت خط شیء [XmlReader](../xmlreader/) را تنظیم می‌کند. |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | مقدارى را تنظیم می‌کند که حداکثر تعداد کاراکترهای مجاز در سند حاصل از گسترش موجودیت‌ها را نشان می‌دهد. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | مقدارى را تنظیم می‌کند که حداکثر تعداد کاراکترهای مجاز در یک سند XML را نشان می‌دهد. مقدار صفر (0) به معنای عدم وجود محدودیت در اندازه سند XML است. مقدار غیر صفر حداکثر اندازه را برحسب کاراکترها مشخص می‌کند. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | [XmlNameTable](../xmlnametable/) مورد استفاده برای مقایسه رشته‌های اتمی را تنظیم می‌کند. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | مقدارى را تنظیم می‌کند که نشان می‌دهد آیا پردازش تعریف نوع سند (DTD) ممنوع شود یا نه. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | XmlSchemaSet مورد استفاده هنگام انجام اعتبارسنجی طرحواره را تنظیم می‌کند. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | مقدارى را تنظیم می‌کند که تنظیمات اعتبارسنجی طرحواره را نشان می‌دهد. این تنظیم برای اشیاء [XmlReader](../xmlreader/) که طرحواره‌ها را اعتبارسنجی می‌کنند (مقدار [XmlReaderSettings::get_ValidationType](./get_validationtype/) برابر [ValidationType::Schema](../validationtype/)) اعمال می‌شود. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | مقدارى را تنظیم می‌کند که نشان می‌دهد آیا [XmlReader](../xmlreader/) هنگام خواندن اعتبارسنجی یا اختصاص نوع انجام می‌دهد یا نه. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | [XmlResolver](../xmlresolver/) مورد استفاده برای دسترسی به اسناد خارجی را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به طور مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری از عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | یک پردازشگر رویداد اضافه می‌کند که هنگام مواجهه خواننده با خطاهای اعتبارسنجی اجرا می‌شود. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | یک پردازشگر رویداد را حذف می‌کند که هنگام مواجهه خواننده با خطاهای اعتبارسنجی اجرا می‌شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlReaderSettings](./xmlreadersettings/)() | یک نمونه جدید از کلاس [XmlReaderSettings](./) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | شرح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## ملاحظات

اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

## مراجع

* کلاس [Object](../../system/object/)
* فضای نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)