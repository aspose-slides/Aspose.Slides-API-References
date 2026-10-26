---
title: XmlSchemaElement
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل العنصر element من مخطط XML كما حددت مؤسسة الويب العالمية (W3C). هذه الفئة هي الفئة الأساسية لجميع أنواع الجسيمات وتستخدم لوصف عنصر في مستند XML.
type: docs
weight: 365
url: /ar/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement فئة


Represents the **العنصر** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This فئة is the الفئة الأساسية for all particle types and is used to describe an عنصر in an XML وثيقة.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## الطرق

| Method | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaNانين متساويتين بالرغم من أن معيار IEC 60559:1989 يوضح أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaNانين متساويتين بالرغم من أن معيار IEC 60559:1989 يوضح أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | يرجع الخاصية **annotation**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | يرجع اشتقاق **Block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | يرجع تفسير ما بعد التجميع لقيمة **Block**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | يرجع مجموعة القيود على العنصر. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | يرجع القيمة الافتراضية للعنصر إذا كان محتواه من نوع بسيط أو كان محتوى العنصر **textOnly**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | يرجع كائن [XmlSchemaType](../xmlschematype/) يمثل نوع العنصر بناءً على قيم [XmlSchemaElement::get_SchemaType](./get_schematype/) أو [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) للعنصر. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | يرجع كائنًا بناءً على [XmlSchemaElement](./) أو [XmlSchemaElement](./) للعنصر، والذي يحمل تفسير ما بعد التجميع لقيمة **ElementType**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | يرجع القيمة **Final** للدلالة على عدم السماح بالمزيد من الاشتقاقات. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | يرجع تفسير ما بعد التجميع للقيمة **Final**. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | يرجع القيمة الثابتة. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | يرجع النموذج للعنصر. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | يرجع المعرف النصي. |
| **bool** [get_IsAbstract](./get_isabstract/)() | يرجع معلومات لتحديد ما إذا كان يمكن استخدام العنصر في مستند نسخة. |
| **bool** [get_IsNillable](./get_isnillable/)() | يرجع معلومات تشير إلى ما إذا كان **xsi:nil** يمكن أن يحدث في بيانات النسخة. يوضح ما إذا كان يمكن تعيين قيمة nil صريحة للعنصر. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | يرجع رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | يرجع موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | يرجع الحد الأقصى لعدد مرات ظهور الجسيم. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | يرجع العدد كقيمة سلسلة. الحد الأقصى لعدد مرات ظهور الجسيم. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | يرجع الحد الأدنى لعدد مرات ظهور الجسيم. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | يرجع العدد كقيمة سلسلة. الحد الأدنى لعدد مرات ظهور الجسيم. |
| [String](../../system/string/) [get_Name](./get_name/)() | يرجع اسم العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | يرجع XmlSerializerNamespaces لاستخدامها مع كائن المخطط هذا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | يرجع أصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | يرجع الاسم المؤهل الفعلي للعنصر المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | يرجع الاسم المرجعي لعنصر تم إعلانها في هذا المخطط (أو مخطط آخر محدد بالمساحة الاسمية المحددة). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | يرجع نوع العنصر. يمكن أن يكون إما نوعًا مركبًا أو نوعًا بسيطًا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | يرجع اسم نوع بيانات مدمج معرف في هذا المخطط أو مخطط آخر محدد بالمساحة الاسمية المحددة. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | يرجع موقع المصدر للملف الذي حمّل المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | يرجع اسم عنصر يتم استبداله بهذا العنصر. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | يرجع السمات المؤهلة التي لا تنتمي إلى مساحة الأسماء المستهدفة للمخطط الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ عملية القفل في عبارة C# lock(). يستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد مرات المرجع المشترك بالقيمة المحددة. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | يضبط الخاصية **annotation**. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يضبط اشتقاق **Block**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | يضبط القيمة الافتراضية للعنصر إذا كان محتواه من نوع بسيط أو كان محتوى العنصر **textOnly**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يضبط القيمة **Final** للدلالة على عدم السماح بمزيد من الاشتقاقات. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | يضبط القيمة الثابتة. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | يضبط النموذج للعنصر. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | يضبط المعرف النصي. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | يضبط معلومات لتحديد ما إذا كان يمكن استخدام العنصر في مستند نسخة. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | يضبط معلومات تشير إلى ما إذا كان **xsi:nil** يمكن أن يحدث في بيانات النسخة. يوضح ما إذا كان يمكن تعيين قيمة nil صريحة للعنصر. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | يضبط رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | يضبط موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | يضبط الحد الأقصى لعدد مرات ظهور الجسيم. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | يضبط العدد كقيمة سلسلة. الحد الأقصى لعدد مرات ظهور الجسيم. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | يضبط الحد الأدنى لعدد مرات ظهور الجسيم. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | يضبط العدد كقيمة سلسلة. الحد الأدنى لعدد مرات ظهور الجسيم. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | يضبط اسم العنصر. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | يضبط XmlSerializerNamespaces لاستخدامها مع كائن المخطط هذا. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | يضبط الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يضبط الاسم المرجعي لعنصر أعلن في هذا المخطط (أو مخطط آخر محدد بالمساحة الاسمية المحددة). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | يضبط نوع العنصر. يمكن أن يكون إما نوعًا مركبًا أو نوعًا بسيطًا. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يضبط اسم نوع بيانات مدمج معرف في هذا المخطط أو مخطط آخر محدد بالمساحة الاسمية. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | يضبط موقع المصدر للملف الذي حمّل المخطط. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يضبط اسم عنصر يتم استبداله بهذا العنصر. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | يضبط السمات المؤهلة التي لا تنتمي إلى مساحة الأسماء المستهدفة للمخطط الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط n من القالب إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد مرات المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدد مرات المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك القفل لبيان C# lock(). يستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد مرات المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد مرات المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlSchemaElement](./xmlschemaelement/)() | يُهيئ نسخة جديدة من الفئة [XmlSchemaElement](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | يُهيئ نسخة جديدة من الفئة [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | يُهيئ نسخة جديدة من الفئة [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | يُدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## التعريفات

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## ملاحظات



يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخ من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط. 

## انظر أيضًا

* الفئة [XmlSchemaParticle](../xmlschemaparticle/)
* مساحة الأسماء [System::Xml::Schema](../)
* مكتبة [Aspose.Slides](../../)