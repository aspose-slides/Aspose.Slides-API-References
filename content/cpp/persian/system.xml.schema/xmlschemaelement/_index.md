---
title: XmlSchemaElement
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر عنصر element از XML Schema است که توسط کنسرسیوم جهانی وب (W3C) مشخص شده است. این کلاس کلاس پایه برای تمام انواع ذره‌ها است و برای توصیف یک عنصر در یک سند XML استفاده می‌شود.
type: docs
weight: 365
url: /fa/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement کلاس

نمایشگر عنصر **element** از XML [Schema](../) است که توسط کنسرسیوم جهانی [Web](../../system.web/) (W3C) مشخص شده است. این کلاس پایه تمام انواع ذرات است و برای توصیف یک عنصر در یک سند XML استفاده می‌شود.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | مقدار ویژگی **annotation** را بر می‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | یک مشتق **Block** را بر می‌گرداند. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | تفسیر پس‌کامپایل مقدار **Block** را بر می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | مجموعه محدودیت‌های عنصر را بر می‌گرداند. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | مقدار پیش‌فرض عنصر را بر می‌گرداند اگر محتوای آن یک نوع ساده باشد یا محتوای عنصر **textOnly** باشد. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | یک شیء [XmlSchemaType](../xmlschematype/) را که نوع عنصر را بر مبنای مقادیر [XmlSchemaElement::get_SchemaType](./get_schematype/) یا [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) عنصر نشان می‌دهد، بر می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | شیئی بر مبنای [XmlSchemaElement](./) یا [XmlSchemaElement](./) عنصر بر می‌گرداند که تفسیر پس‌کامپایل مقدار **ElementType** را نگه می‌دارد. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | مقدار **Final** را بر می‌گرداند تا نشان دهد هیچ مشتق دیگری مجاز نیست. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | تفسیر پس‌کامپایل مقدار **Final** را بر می‌گرداند. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | مقدار ثابت را بر می‌گرداند. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | فرم عنصر را بر می‌گرداند. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | شناسه رشته‌ای را بر می‌گرداند. |
| **bool** [get_IsAbstract](./get_isabstract/)() | اطلاعاتی را بر می‌گرداند که نشان می‌دهد آیا عنصر می‌تواند در سند نمونه استفاده شود یا نه. |
| **bool** [get_IsNillable](./get_isnillable/)() | اطلاعاتی را بر می‌گرداند که نشان دهد آیا **xsi:nil** می‌تواند در داده‌های نمونه حضور داشته باشد. نشان می‌دهد آیا مقدار صفر صریح می‌تواند به عنصر اختصاص یابد. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | شماره خط در فایلی که عنصر **schema** به آن ارجاع می‌دهد را بر می‌گرداند. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | موقعیت خط در فایلی که عنصر **schema** به آن ارجاع می‌دهد را بر می‌گرداند. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | حداکثر تعداد دفعاتی که ذره می‌تواند رخ دهد را بر می‌گرداند. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | عدد را به صورت مقدار رشته‌ای بر می‌گرداند. حداکثر تعداد دفعاتی که ذره می‌تواند رخ دهد. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | حداقل تعداد دفعاتی که ذره می‌تواند رخ دهد را بر می‌گرداند. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | عدد را به صورت مقدار رشته‌ای بر می‌گرداند. حداقل تعداد دفعاتی که ذره می‌تواند رخ دهد. |
| [String](../../system/string/) [get_Name](./get_name/)() | نام عنصر را بر می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | XmlSerializerNamespaces را که برای این شیء schema استفاده می‌شود بر می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | والد این [XmlSchemaObject](../xmlschemaobject/) را بر می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | نام معتبر واقعی برای عنصر داده شده را بر می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | نام مرجع یک عنصر که در این schema (یا در schema دیگری که با فضای نام مشخص شده) اعلام شده است را بر می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | نوع عنصر را بر می‌گرداند. این می‌تواند یک نوع پیچیده یا نوع ساده باشد. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | نام یک نوع داده داخلی که در این schema یا در schema دیگری که با فضای نام مشخص شده تعریف شده است را بر می‌گرداند. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | محل منبع فایلی که schema را بارگذاری کرده است را بر می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | نام عنصری که توسط این عنصر جایگزین می‌شود را بر می‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | ویژگی‌های معتبر که به فضای نام هدف schema فعلی تعلق ندارند را بر می‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌سازی اشیاء سفارشی را ممکن می‌سازد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرا کننده قفل کردن با بیان C# lock(). مستقیماً صدا بزنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. همه ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را بر حسب مقدار مشخص کاهش می‌دهد. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ویژگی **annotation** را تنظیم می‌کند. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | یک مشتق **Block** را تنظیم می‌کند. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | مقدار پیش‌فرض عنصر را تنظیم می‌کند اگر محتوای آن یک نوع ساده باشد یا محتوای عنصر **textOnly** باشد. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | مقدار **Final** را تنظیم می‌کند تا نشان دهد هیچ مشتق دیگری مجاز نیست. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | مقدار ثابت را تنظیم می‌کند. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | فرم عنصر را تنظیم می‌کند. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | شناسه رشته‌ای را تنظیم می‌کند. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | اطلاعاتی را تنظیم می‌کند که نشان دهد آیا عنصر می‌تواند در سند نمونه استفاده شود یا نه. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | اطلاعاتی را تنظیم می‌کند که نشان دهد آیا **xsi:nil** می‌تواند در داده‌های نمونه حضور داشته باشد. نشان می‌دهد آیا مقدار صفر صریح می‌تواند به عنصر اختصاص یابد. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | شماره خط در فایلی که عنصر **schema** به آن ارجاع می‌دهد را تنظیم می‌کند. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | موقعیت خط در فایلی که عنصر **schema** به آن ارجاع می‌دهد را تنظیم می‌کند. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | حداکثر تعداد دفعاتی که ذره می‌تواند رخ دهد را تنظیم می‌کند. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | عدد را به صورت مقدار رشته‌ای تنظیم می‌کند. حداکثر تعداد دفعاتی که ذره می‌تواند رخ دهد. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | حداقل تعداد دفعاتی که ذره می‌تواند رخ دهد را تنظیم می‌کند. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | عدد را به صورت مقدار رشته‌ای تنظیم می‌کند. حداقل تعداد دفعاتی که ذره می‌تواند رخ دهد. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | نام عنصر را تنظیم می‌کند. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | XmlSerializerNamespaces را که برای این شیء schema استفاده می‌شود، تنظیم می‌کند. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | والد این [XmlSchemaObject](../xmlschemaobject/) را تنظیم می‌کند. |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | نام مرجع یک عنصر که در این schema (یا در schema دیگری که با فضای نام مشخص شده) اعلام شده است را تنظیم می‌کند. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | نوع عنصر را تنظیم می‌کند. این می‌تواند یک نوع پیچیده یا نوع ساده باشد. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | نام یک نوع داده داخلی که در این schema یا در schema دیگری که با فضای نام مشخص شده تعریف شده است را تنظیم می‌کند. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | محل منبع فایلی که schema را بارگذاری کرده است را تنظیم می‌کند. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | نام عنصری که توسط این عنصر جایگزین می‌شود را تنظیم می‌کند. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ویژگی‌های معتبر که به فضای نام هدف schema فعلی تعلق ندارند را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). تبدیل اشیاء سفارشی به رشته را ممکن می‌سازد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای سازنده C# typeof([System.Object](../../system/object/)) را پیاده می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل C# lock(). مستقیماً صدا بزنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlSchemaElement](./xmlschemaelement/)() | نمونه جدیدی از کلاس [XmlSchemaElement](./) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | نمونه جدیدی از کلاس [XmlSchemaObject](../xmlschemaobject/) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | نمونه جدیدی از کلاس [XmlSchemaParticle](../xmlschemaparticle/) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## تعاریف

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک مستعار برای اشاره‌گر مشترک به نمونه‌ای از این کلاس. |
## ملاحظات

شیءهای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید.

## همچنین ببینید

* کلاس [XmlSchemaParticle](../xmlschemaparticle/)
* فضای‌نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)