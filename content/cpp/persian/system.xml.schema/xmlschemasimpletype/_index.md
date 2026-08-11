---
title: XmlSchemaSimpleType
second_title: مرجع API Aspose.Slides برای C++
description: نمایش دهندهٔ عنصر simpleType برای محتوی ساده از XML Schema طبق مشخصات کنسرسیوم جهانی وب (W3C). این کلاس یک نوع ساده را تعریف می‌کند. انواع ساده می‌توانند اطلاعات و محدودیت‌ها را برای مقدار ویژگی‌ها یا عناصری که فقط متن دارند، مشخص کنند.
type: docs
weight: 833
url: /fa/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType کلاس

نمایش دهندهٔ عنصر **simpleType** برای محتوی ساده از XML [Schema](../) طبق کنسرسیوم جهانی [Web](../../system.web/) (W3C) است. این کلاس یک نوع ساده را تعریف می‌کند. انواع ساده می‌توانند اطلاعات و محدودیت‌ها را برای مقدار ویژگی‌ها یا عناصر با محتوای فقط متنی مشخص کنند.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## متدها

| روش | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر مطابق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر مطابق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | ویژگی **annotation** را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | نوع شیء پس از کامپایل یا نوع دادهٔ داخلی XML [Schema](../) Definition Language (XSD)، عنصر simpleType یا عنصر complexType را برمی‌گرداند. این یک مقدار infoset پس از کامپایل اسکیما است. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | مقدار پس از کامپایل برای نوع پایهٔ این نوع اسکیما را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\> [get_Content](./get_content/)() | یکی از [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/)، [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) یا [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/) را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | مقدار پس از کامپایل برای نوع دادهٔ نوع پیچیده را برمی‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | اطلاعات پس از کامپایل دربارهٔ نحوهٔ استخراج این عنصر از نوع پایهٔ خود را برمی‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | ویژگی نهایی مشتق نوع که نشان می‌دهد آیا مشتقات بیشتر مجاز هستند را برمی‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | تعبیر پس از کامپایل مقدار [XmlSchemaType::get_Final](../xmlschematype/get_final/) را برمی‌گرداند. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | شناسهٔ رشته‌ای را برمی‌گرداند. |
| virtual **bool** [get_IsMixed](../xmlschematype/get_ismixed/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا این نوع مدل محتوای ترکیبی دارد. این فراخوانی فقط در یک نوع پیچیده معتبر است. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | شماره خط در فایلی که عنصر **schema** به آن اشاره دارد را برمی‌گرداند. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | موقعیت ستون در فایلی که عنصر **schema** به آن اشاره دارد را برمی‌گرداند. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | نام نوع را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | XmlSerializerNamespaces برای استفاده با این شیء اسکیما را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | والد این [XmlSchemaObject](../xmlschemaobject/) را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | نام کامل برای نوع ساخته‌شده از ویژگی **Name** این نوع را برمی‌گرداند. این مقدار پس از کامپایل اسکیما است. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | موقعیت منبع برای فایلی که اسکیما را بارگیری کرده است را برمی‌گرداند. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | XmlTypeCode نوع را برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | ویژگی‌های کاملاً تعیین‌شده‌ای که به فضای نام هدف اسکیما فعلی تعلق ندارند را برمی‌گرداند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | یک [XmlSchemaComplexType](../xmlschemacomplextype/) را برمی‌گرداند که نوع پیچیدهٔ داخلی نوع پیچیدهٔ مشخص‌شده را نمایان می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | یک [XmlSchemaComplexType](../xmlschemacomplextype/) را برمی‌گرداند که نوع پیچیدهٔ داخلی نوع پیچیدهٔ مشخص‌شده توسط نام کامل را نمایان می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | یک [XmlSchemaSimpleType](./) را برمی‌گرداند که نوع سادهٔ داخلی نوع ساده‌ای که توسط نام کامل مشخص شده را نمایان می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | یک [XmlSchemaSimpleType](./) را برمی‌گرداند که نوع سادهٔ داخلی نوع سادهٔ مشخص‌شده را نمایان می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌گذاری اشیاء سفارشی را ممکن می‌سازد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | مقداری را برمی‌گرداند که نشان می‌دهد آیا نوع اسکیما مشتق‌شدهٔ مشخص‌شده از نوع اسکیما پایهٔ مشخص‌شده مشتق شده است. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مهار [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌گذاری انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. همه ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr از طریق مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ویژگی **annotation** را تنظیم می‌کند. |
| void [set_Content](./set_content/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\>\&) | یکی از [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/)، [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) یا [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/) را تنظیم می‌کند. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ویژگی نهایی مشتق نوع که نشان می‌دهد آیا مشتقات بیشتر مجاز هستند را تنظیم می‌کند. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | شناسهٔ رشته‌ای را تنظیم می‌کند. |
| virtual void [set_IsMixed](../xmlschematype/set_ismixed/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا این نوع مدل محتوای ترکیبی دارد. این فراخوانی فقط در یک نوع پیچیده معتبر است. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | شماره خط در فایلی که عنصر **schema** به آن اشاره دارد را تنظیم می‌کند. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | موقعیت ستون در فایلی که عنصر **schema** به آن اشاره دارد را تنظیم می‌کند. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | نام نوع را تنظیم می‌کند. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | XmlSerializerNamespaces برای استفاده با این شیء اسکیما را تنظیم می‌کند. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | والد این [XmlSchemaObject](../xmlschemaobject/) را تنظیم می‌کند. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | موقعیت منبع برای فایلی که اسکیما را بارگذاری کرده است را تنظیم می‌کند. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ویژگی‌های کاملاً تعیین‌شده‌ای که به فضای نام هدف اسکیما فعلی تعلق ندارند را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری عبارت C# lock() را باز می‌کند. مستقیم فراخوانی کنید یا از شیء مهار [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | یک نمونهٔ جدید از کلاس [XmlSchemaObject](../xmlschemaobject/) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaSimpleType](./xmlschemasimpletype/)() | یک نمونهٔ جدید از کلاس [XmlSchemaSimpleType](./) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | یک نمونهٔ جدید از کلاس [XmlSchemaType](../xmlschematype/) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعریف‌های نوع

| تعریف | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس است. |

## ملاحظات

اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. 

## مراجع

* کلاس [XmlSchemaType](../xmlschematype/)
* فضای‌نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)