---
title: XmlSchemaInclude
second_title: مرجع API Aspose.Slides برای C++
description: عنصر include را از XML Schema مطابق با World Wide Web Consortium (W3C) نشان می‌دهد. این کلاس برای گنجاندن اعلان‌ها و تعریف‌ها از یک طرح خارجی استفاده می‌شود. اعلان‌ها و تعریف‌های گنجانده‌شده سپس برای پردازش در طرح شامل‌کننده در دسترس هستند.
type: docs
weight: 495
url: /fa/system.xml.schema/xmlschemainclude/
---
## XmlSchemaInclude کلاس

Represents the **include** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is used to include declarations and definitions from an external schema. The included declarations and definitions are then available for processing in the containing schema.

```cpp
class XmlSchemaInclude : public System::Xml::Schema::XmlSchemaExternal
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از مفهوم [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](./get_annotation/)() | مقدار **annotation** را باز می‌گرداند. |
| [String](../../system/string/) [get_Id](../xmlschemaexternal/get_id/)() | شناسه رشته‌ای را باز می‌گرداند. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | شماره خط در فایلی که عنصر **schema** به آن اشاره دارد را باز می‌گرداند. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | موقعیت خط در فایلی که عنصر **schema** به آن اشاره دارد را باز می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | XmlSerializerNamespaces را که برای این شیء schema استفاده می‌شود، باز می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | والد این [XmlSchemaObject](../xmlschemaobject/) را باز می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [get_Schema](../xmlschemaexternal/get_schema/)() | [XmlSchema](../xmlschema/) مربوط به schema ارجاع‌شده را باز می‌گرداند. |
| [String](../../system/string/) [get_SchemaLocation](../xmlschemaexternal/get_schemalocation/)() | محل Uniform Resource Identifier (URI) برای schema را باز می‌گرداند که به پردازشگر schema می‌گوید schema فیزیکی کجا قرار دارد. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | محل منبع فایل بارگذاری شده توسط schema را باز می‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaexternal/get_unhandledattributes/)() | ویژگی‌های qualified را که به فضای نام هدف schema تعلق ندارند، باز می‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را به دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به دست می‌آورد. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است یا خیر. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء پاسدار [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کلاس‌های مشتق از طریق کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کلاس‌های مشتق از طریق کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌ایی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | عدد شمارنده مرجع مشترک را با مقدار مشخص کاهش می‌دهد. |
| void [set_Annotation](./set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | مقدار **annotation** را تنظیم می‌کند. |
| void [set_Id](../xmlschemaexternal/set_id/)(const [String](../../system/string/)\&) | شناسه رشته‌ای را تنظیم می‌کند. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | شماره خط در فایلی که عنصر **schema** به آن اشاره دارد را تنظیم می‌کند. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | موقعیت خط در فایلی که عنصر **schema** به آن اشاره دارد را تنظیم می‌کند. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | XmlSerializerNamespaces را که برای این شیء schema استفاده می‌شود، تنظیم می‌کند. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | والد این [XmlSchemaObject](../xmlschemaobject/) را تنظیم می‌کند. |
| void [set_Schema](../xmlschemaexternal/set_schema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | [XmlSchema](../xmlschema/) مربوط به schema ارجاع‌شده را تنظیم می‌کند. |
| void [set_SchemaLocation](../xmlschemaexternal/set_schemalocation/)(const [String](../../system/string/)\&) | محل Uniform Resource Identifier (URI) برای schema را تنظیم می‌کند که به پردازشگر schema می‌گوید schema فیزیکی کجا قرار دارد. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | محل منبع فایل بارگذاری شده توسط schema را تنظیم می‌کند. |
| void [set_UnhandledAttributes](../xmlschemaexternal/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ویژگی‌های qualified را که به فضای نام هدف schema تعلق ندارند، تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر Weak تنظیم می‌کند (به‌جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارنده مرجع مشترک را به دست می‌آورد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء پاسدار [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده weak را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده weak را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlSchemaExternal](../xmlschemaexternal/xmlschemaexternal/)() | نمونه جدیدی از کلاس [XmlSchemaExternal](../xmlschemaexternal/) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaInclude](./xmlschemainclude/)() | نمونه جدیدی از کلاس [XmlSchemaInclude](./) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | نمونه جدیدی از کلاس [XmlSchemaObject](../xmlschemaobject/) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تعریف‌های نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## ملاحظات

شیء‌های این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را درون اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید.

## مراجع

* کلاس [XmlSchemaExternal](../xmlschemaexternal/)
* فضای نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)