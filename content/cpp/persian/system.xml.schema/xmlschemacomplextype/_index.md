---
title: XmlSchemaComplexType
second_title: "مرجع API Aspose.Slides برای C++"
description: "نماد عنصر complexType از XML Schema مطابق مشخصات کنسرسیوم جهانی وب (W3C) است. این کلاس یک نوع پیچیده را تعریف می‌کند که مجموعهٔ ویژگی‌ها و محتوای یک عنصر را تعیین می‌کند."
type: docs
weight: 300
url: /fa/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType کلاس

نماد **complexType** از XML [Schema](../) را مطابق مشخصات کنسرسیوم جهانی [Web](../../system.web/) (W3C) نشان می‌دهد. این کلاس یک نوع پیچیده را تعریف می‌کند که مجموعه‌ای از ویژگی‌ها و محتواهای یک عنصر را تعیین می‌کند.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## متدها

| Method | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از semantics C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه عدد شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه عدد شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | ویژگی **annotation** را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | مقدار مولفه [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) نوع پیچیده را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | مجموعهٔ ویژگی‌های نوع پیچیده را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | مجموعهٔ تمام ویژگی‌های ترکیب‌شدهٔ این نوع پیچیده و نوع‌های پایهٔ آن را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | مقدار post-compilation برای **anyAttribute** این نوع پیچیده و نوع(های) پایهٔ آن را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | نوع شیء post-compilation یا نوع دادهٔ داخلی XML [Schema](../) Definition Language (XSD)، عنصر simpleType یا عنصر complexType را برمی‌گرداند. این یک مقدار infoset پس از کامپایل‌اسکیما است. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | مقدار post-compilation برای نوع پایهٔ این نوع اسکیما را برمی‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | ویژگی **block** را برمی‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | مقدار پس از کامپایل نوع به infoset پس از اعتبارسنجی اسکیما را برمی‌گرداند. این مقدار نشان می‌دهد که نوع چگونه هنگام استفاده از **xsi:type** در سند نمونه اعمال می‌شود. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | [XmlSchemaContentModel](../xmlschemacontentmodel/) post-compilation این نوع پیچیده را برمی‌گرداند. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | مدل محتوا (content model) نوع پیچیده را که مقدار post-compilation را در خود دارد برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | ذره‌ای که مقدار post-compilation ذره [XmlSchemaComplexType::get_ContentType](./get_contenttype/) را در خود دارد برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | مقدار post-compilation برای نوع دادهٔ نوع پیچیده را برمی‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | اطلاعات post-compilation دربارهٔ چگونگی استخراج این عنصر از نوع پایهٔ آن را برمی‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | ویژگی نهایی مشتق‌گیری نوع را که نشان می‌دهد آیا مشتق‌گیری‌های بیشتر مجاز هستند یا نه، برمی‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | تفسیر post-compilation مقدار [XmlSchemaType::get_Final](../xmlschematype/get_final/) را برمی‌گرداند. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | شناسهٔ رشته‌ای را برمی‌گرداند. |
| **bool** [get_IsAbstract](./get_isabstract/)() | اطلاعاتی را برمی‌گرداند که تعیین می‌کند آیا عنصر **complexType** می‌تواند در سند نمونه استفاده شود یا نه. |
| **bool** [get_IsMixed](./get_ismixed/)() override | اطلاعاتی را برمی‌گرداند که تعیین می‌کند آیا نوع پیچیده دارای مدل محتوا ترکیبی (نشانه‌گذاری در داخل محتوا) است یا نه. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | شمارهٔ خط در فایلی که عنصر **schema** به آن اشاره دارد را برمی‌گرداند. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | موقعیت ستون در فایلی که عنصر **schema** به آن اشاره دارد را برمی‌گرداند. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | نام نوع را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | XmlSerializerNamespaces را که برای این شیء اسکیما استفاده می‌شود برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | والد این [XmlSchemaObject](../xmlschemaobject/) را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | نوع کامپوزیتور را به عنوان یکی از کلاس‌های [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) یا [XmlSchemaSequence](../xmlschemasequence/) برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | نام Qualified برای نوع ساخته‌شده از ویژگی **Name** این نوع را برمی‌گرداند. این یک مقدار post-schema-compilation است. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | محل منبع فایلی که اسکیما را بارگذاری کرده است را برمی‌گرداند. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | XmlTypeCode نوع را برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | ویژگی‌های Qualified که به فضای نام هدف اسکیما فعلی تعلق ندارند را برمی‌گرداند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | یک [XmlSchemaComplexType](./) که نوع پیچیده داخلی نوع پیچیده مشخص‌شده را نشان می‌دهد برمی‌گرداند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | یک [XmlSchemaComplexType](./) که نوع پیچیده داخلی نوع پیچیده مشخص‌شده با نام Qualified را نشان می‌دهد برمی‌گرداند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | یک [XmlSchemaSimpleType](../xmlschemasimpletype/) که نوع ساده داخلی نوع ساده مشخص‌شده با نام Qualified را نشان می‌دهد برمی‌گرداند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | یک [XmlSchemaSimpleType](../xmlschemasimpletype/) که نوع ساده داخلی نوع ساده مشخص‌شده را نشان می‌دهد برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | مقداریتی را برمی‌گرداند که نشان می‌دهد آیا نوع اسکیما مشتق‌شدهٔ مشخص‌شده از نوع اسکیما پایهٔ مشخص‌شده مشتق شده است یا نه. |
| void [Lock](../../system/object/lock/)() | قفل کردن توسط عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق‌شده را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. واقعاً هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق‌شده را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع‌دار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ویژگی **annotation** را تنظیم می‌کند. |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | مقدار مولفه [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) نوع پیچیده را تنظیم می‌کند. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ویژگی **block** را تنظیم می‌کند. |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | [XmlSchemaContentModel](../xmlschemacontentmodel/) post-compilation این نوع پیچیده را تنظیم می‌کند. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ویژگی نهایی مشتق‌گیری نوع را که نشان می‌دهد آیا مشتق‌گیری‌های بیشتر مجاز هستند یا نه، تنظیم می‌کند. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | شناسهٔ رشته‌ای را تنظیم می‌کند. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | اطلاعاتی را تنظیم می‌کند که تعیین می‌کند آیا عنصر **complexType** می‌تواند در سند نمونه استفاده شود یا نه. |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | اطلاعاتی را تنظیم می‌کند که تعیین می‌کند آیا نوع پیچیده دارای مدل محتوا ترکیبی (نشانه‌گذاری در داخل محتوا) است یا نه. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | شمارهٔ خط در فایلی که عنصر **schema** به آن اشاره دارد را تنظیم می‌کند. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | موقعیت ستون در فایلی که عنصر **schema** به آن اشاره دارد را تنظیم می‌کند. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | نام نوع را تنظیم می‌کند. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | XmlSerializerNamespaces را که برای این شیء اسکیما استفاده می‌شود تنظیم می‌کند. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | والد این [XmlSchemaObject](../xmlschemaobject/) را تنظیم می‌کند. |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | نوع کامپوزیتور را به عنوان یکی از کلاس‌های [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) یا [XmlSchemaSequence](../xmlschemasequence/) تنظیم می‌کند. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | محل منبع فایلی که اسکیما را بارگذاری کرده است را تنظیم می‌کند. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ویژگی‌های Qualified که به فضای نام هدف اسکیما فعلی تعلق ندارند را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. اجازه می‌دهد اشاره‌گرها در کانتینرها به حالت weak تغییر یابند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری توسط عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌مرگ‌های هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌مرگ‌های هوشمند یا ThisProtector استفاده کنید. |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | یک نمونهٔ جدید از کلاس [XmlSchemaComplexType](./) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | یک نمونهٔ جدید از کلاس [XmlSchemaObject](../xmlschemaobject/) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | یک نمونهٔ جدید از کلاس [XmlSchemaType](../xmlschematype/) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را уничтож می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## ملاحظات

اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید.

## همچنین ببینید

* کلاس [XmlSchemaType](../xmlschematype/)
* فضای‌نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)