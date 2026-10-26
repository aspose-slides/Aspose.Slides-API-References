---
title: XmlSchemaValidator
second_title: Aspose.Slides برای C++ مرجع API
description: یک موتور اعتبارسنجی اسکیما XML Schema Definition Language (XSD) را نشان می‌دهد. کلاس XmlSchemaValidator نمی‌تواند ارث‌بری شود.
type: docs
weight: 937
url: /fa/system.xml.schema/xmlschemavalidator/
---
## کلاس XmlSchemaValidator

Represents an XML [Schema](../) Definition Language (XSD) [Schema](../) validation engine. The [XmlSchemaValidator](./) class cannot be inherited.

```cpp
class XmlSchemaValidator : public System::Object
```

## متدها

| متد | توضیحات |
| --- | --- |
| void [AddSchema](./addschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | یک اسکیما XML [Schema](../) Definition Language (XSD) به مجموعه اسکیماهای مورد استفاده برای اعتبارسنجی اضافه می‌کند. |
| void [EndValidation](./endvalidation/)() | اعتبارسنجی را پایان می‌دهد و محدودیت‌های هویت را برای کل سند XML بررسی می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌ساز می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌ساز می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\> [get_LineInfoProvider](./get_lineinfoprovider/)() | اطلاعات شماره خط را برای گره XML که در حال اعتبارسنجی است برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_SourceUri](./get_sourceuri/)() | آدرس منبع (URI) را برای گره XML که در حال اعتبارسنجی است برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ValidationEventSender](./get_validationeventsender/)() | شیء ارسال‌شده به‌عنوان فرستندهٔ یک رویداد اعتبارسنجی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\> [GetExpectedAttributes](./getexpectedattributes/)() | ویژگی‌های مورد انتظار برای زمینهٔ عنصر فعلی را برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\> [GetExpectedParticles](./getexpectedparticles/)() | ذرات مورد انتظار در زمینهٔ عنصر فعلی را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| void [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>\&) | محدودیت‌های هویت را بر روی ویژگی‌های پیش‌فرض اعتبارسنجی می‌کند و لیست مشخص‌شده را با اشیاء [XmlSchemaAttribute](../xmlschemaattribute/) برای هر ویژگی با مقدار پیش‌فرض که پیش از این با روش [XmlSchemaValidator::ValidateAttribute](./validateattribute/) در زمینه عنصر اعتبارسنجی نشده‌اند، پر می‌کند. |
| void [Initialize](./initialize/)() | وضعیت شیء [XmlSchemaValidator](./) را مقداردهی اولیه می‌کند. |
| void [Initialize](./initialize/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | وضعیت شیء [XmlSchemaValidator](./) را با استفاده از [XmlSchemaObject](../xmlschemaobject/) مشخص‌شده برای اعتبارسنجی جزئی مقداردهی اولیه می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل-گذاری دستور lock() در C#. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلونینگ انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های مشتق‌شده را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های مشتق‌شده را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع به اشتراک‌گذاری را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_LineInfoProvider](./set_lineinfoprovider/)(const [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\>\&) | اطلاعات شماره خط را برای گره XML که در حال اعتبارسنجی است تنظیم می‌کند. |
| void [set_SourceUri](./set_sourceuri/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | آدرس منبع (URI) را برای گره XML که در حال اعتبارسنجی است تنظیم می‌کند. |
| void [set_ValidationEventSender](./set_validationeventsender/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | شیء ارسال‌شده به‌عنوان فرستندهٔ یک رویداد اعتبارسنجی را تنظیم می‌کند. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | شیء [XmlResolver](../../system.xml/xmlresolver/) را که برای حل **xs:import** و **xs:include** و همچنین ویژگی‌های **xsi:schemaLocation** و **xsi:noNamespaceSchemaLocation** استفاده می‌شود، تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به‌صورت اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع به اشتراک‌گذاری را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع به اشتراک‌گذاری را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع به اشتراک‌گذاری را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [SkipToEndElement](./skiptoendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | اعتبارسنجی محتوای عنصر فعلی را صرف‌نظر می‌کند و شیء [XmlSchemaValidator](./) را برای اعتبارسنجی محتوا در زمینهٔ عنصر والد آماده می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | نام ویژگی، URI فضای‌نام، و مقدار را در زمینهٔ عنصر فعلی اعتبارسنجی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [XmlValueGetter](../xmlvaluegetter/), const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | نام ویژگی، URI فضای‌نام، و مقدار را در زمینهٔ عنصر فعلی اعتبارسنجی می‌کند. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | عنصر را در زمینهٔ فعلی اعتبارسنجی می‌کند. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | عنصر را در زمینهٔ فعلی با مقادیر ویژگی‌های **xsi:Type**، **xsi:Nil**، **xsi:SchemaLocation** و **xsi:NoNamespaceSchemaLocation** مشخص‌شده اعتبارسنجی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | بررسی می‌کند که آیا محتوای متنی عنصر مطابق با نوع دادهٔ آن برای عناصری با محتوی ساده معتبر است و آیا محتوای عنصر فعلی برای عناصری با محتوی پیچیده کامل است یا خیر. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | بررسی می‌کند که آیا محتوای متنی عنصر مشخص‌شده مطابق با نوع دادهٔ آن معتبر است. |
| void [ValidateEndOfAttributes](./validateendofattributes/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | بررسی می‌کند که آیا همهٔ ویژگی‌های ضروری در زمینهٔ عنصر حضور دارند و شیء [XmlSchemaValidator](./) را برای اعتبارسنجی محتوای فرزند عنصر آماده می‌کند. |
| void [ValidateText](./validatetext/)(const [String](../../system/string/)\&) | بررسی می‌کند که آیا رشتهٔ متنی مشخص‌شده در زمینهٔ عنصر فعلی مجاز است و اگر عنصر فعلی محتوی ساده داشته باشد، متن را برای اعتبارسنجی جمع‌آوری می‌کند. |
| void [ValidateText](./validatetext/)([XmlValueGetter](../xmlvaluegetter/)) | بررسی می‌کند که آیا متنی که توسط شیء XmlValueGetter مشخص‌شده برگشت داده می‌شود در زمینهٔ عنصر فعلی مجاز است و اگر عنصر فعلی محتوی ساده داشته باشد، متن را برای اعتبارسنجی جمع‌آوری می‌کند. |
| void [ValidateWhitespace](./validatewhitespace/)(const [String](../../system/string/)\&) | بررسی می‌کند که آیا فضای سفید در رشتهٔ مشخص‌شده در زمینهٔ عنصر فعلی مجاز است و اگر عنصر فعلی محتوی ساده داشته باشد، فضای سفید را برای اعتبارسنجی جمع‌آوری می‌کند. |
| void [ValidateWhitespace](./validatewhitespace/)([XmlValueGetter](../xmlvaluegetter/)) | بررسی می‌کند که آیا فضای سفید که توسط شیء XmlValueGetter مشخص‌شده برگردانده می‌شود در زمینهٔ عنصر فعلی مجاز است و اگر عنصر فعلی محتوی ساده داشته باشد، فضای سفید را برای اعتبارسنجی جمع‌آوری می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlSchemaValidator](./xmlschemavalidator/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&, [XmlSchemaValidationFlags](../xmlschemavalidationflags/)) | یک نمونهٔ جدید از کلاس [XmlSchemaValidator](./) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر اشتراکی به یک نمونه از این کلاس. |

## ملاحظات

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)