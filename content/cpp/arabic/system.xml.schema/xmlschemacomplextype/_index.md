---
title: XmlSchemaComplexType
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل عنصر complexType من مخطط XML كما هو محدد من قبل اتحاد الويب العالمي (W3C). يعرّف هذا الصنف نوعًا مركّبًا يحدد مجموعة السمات ومحتوى العنصر.
type: docs
weight: 300
url: /ar/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType صنف


يمثل عنصر **complexType** من XML [Schema](../) كما هو محدد من قبل اتحاد الويب العالمي [Web](../../system.web/) (W3C). يعرّف هذا الصنف نوعًا مركّبًا يحدد مجموعة السمات ومحتوى العنصر.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | يعيد الخاصية **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | يعيد القيمة للمكوّن [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) من النوع المركّب. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | يعيد مجموعة السمات للنوع المركّب. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | يعيد مجموعة جميع السمات المتوافقة لهذا النوع المركّب وأنواعه الأساسية. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | يعيد القيمة بعد التجميع لـ **anyAttribute** لهذا النوع المركّب وأنواعها الأساسية. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | يعيد نوع الكائن بعد التجميع أو نوع البيانات المعرّف بلغة تعريف XML [Schema](../) (XSD) المدمجة، أو عنصر simpleType، أو عنصر complexType. هذه قيمة مجموعة معلومات بعد تجميع المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | يعيد القيمة بعد التجميع لنوع الأساس لهذا النوع من المخطط. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | يعيد الخاصية **block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | يعيد القيمة بعد تجميع النوع إلى مجموعة معلومات ما بعد التحقق من صحة المخطط (infoset). تشير هذه القيمة إلى كيفية فرض النوع عند استخدام **xsi:type** في مستند الحالة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | يعيد [XmlSchemaContentModel](../xmlschemacontentmodel/) بعد التجميع لهذا النوع المركّب. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | يعيد نموذج المحتوى للنوع المركّب الذي يحتوي على القيمة بعد التجميع. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | يعيد الجسيم الذي يحمل القيمة بعد التجميع للجسيم [XmlSchemaComplexType::get_ContentType](./get_contenttype/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | يعيد القيمة بعد التجميع لنوع البيانات للنوع المركّب. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | يعيد معلومات ما بعد التجميع حول كيفية اشتقاق هذا العنصر من نوعه الأساسي. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | يعيد السمة النهائية لاشتقاق النوع التي تشير إلى ما إذا كان السماح باشتقاقات إضافية. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | يعيد تفسير [XmlSchemaType::get_Final](../xmlschematype/get_final/) بعد التجميع. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | يعيد معرف السلسلة. |
| **bool** [get_IsAbstract](./get_isabstract/)() | يعيد المعلومات التي تحدد ما إذا كان يمكن استخدام عنصر **complexType** في مستند الحالة. |
| **bool** [get_IsMixed](./get_ismixed/)() override | يعيد المعلومات التي تحدد ما إذا كان للنوع المركب نموذج محتوى مختلط (علامات داخل المحتوى). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | يعيد رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | يعيد موضع العمود في الملف الذي يشير إليه عنصر **schema**. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | يعيد اسم النوع. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | يعيد XmlSerializerNamespaces لاستخدامها مع كائن المخطط هذا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | يعيد الوالد لهذا [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | يعيد نوع المُركّب كأحد أصناف [XmlSchemaGroupRef](../xmlschemagroupref/)، [XmlSchemaChoice](../xmlschemachoice/)، [XmlSchemaAll](../xmlschemaall/)، أو [XmlSchemaSequence](../xmlschemasequence/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | يعيد الاسم المؤهل للنوع المبني من صفة **Name** لهذا النوع. هذه قيمة بعد تجميع المخطط. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | يعيد موقع المصدر للملف الذي حمّل المخطط. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | يعيد XmlTypeCode للنوع. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | يعيد السمات المؤهلة التي لا تنتمي إلى مساحة اسم الهدف الحالية للمخطط. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | يعيد [XmlSchemaComplexType](./) التي تمثّل النوع المركّب المدمج للنوع المركّب المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يعيد [XmlSchemaComplexType](./) التي تمثّل النوع المركّب المدمج للنوع المركّب المحدد بالاسم المؤهل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يعيد [XmlSchemaSimpleType](../xmlschemasimpletype/) التي تمثّل النوع البسيط المدمج للنوع البسيط المحدد بالاسم المؤهل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | يعيد [XmlSchemaSimpleType](../xmlschemasimpletype/) التي تمثّل النوع البسيط المدمج للنوع البسيط المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل مثالا من النوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يعيد قيمة تشير إلى ما إذا كان نوع المخطط المشتق المحدد مشتقًا من نوع المخطط الأساسي المحدد. |
| void [Lock](../../system/object/lock/)() | ينفّذ إقفال عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات عبر المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات عبر المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | يضبط خاصية **annotation**. |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | يضبط القيمة للمكوّن [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) من النوع المركّب. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يضبط الخاصية **block**. |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | يضبط [XmlSchemaContentModel](../xmlschemacontentmodel/) بعد التجميع لهذا النوع المركّب. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يضبط السمة النهائية لاشتقاق النوع التي تشير إلى ما إذا كان السماح باشتقاقات إضافية. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | يضبط معرف السلسلة. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | يضبط المعلومات التي تحدد ما إذا كان عنصر **complexType** يمكن استخدامه في مستند الحالة. |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | يضبط المعلومات التي تحدد ما إذا كان للنوع المركب نموذج محتوى مختلط (علامات داخل المحتوى). |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | يضبط رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | يضبط موضع العمود في الملف الذي يشير إليه عنصر **schema**. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | يضبط اسم النوع. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | يضبط XmlSerializerNamespaces لاستخدامها مع كائن المخطط هذا. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | يضبط الوالد لهذا [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | يضبط نوع المُركّب كأحد أصناف [XmlSchemaGroupRef](../xmlschemagroupref/)، [XmlSchemaChoice](../xmlschemachoice/)، [XmlSchemaAll](../xmlschemaall/) أو [XmlSchemaSequence](../xmlschemasequence/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | يضبط موقع المصدر للملف الذي حمّل المخطط. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | يضبط السمات المؤهلة التي لا تنتمي إلى مساحة اسم الهدف الحالية للمخطط. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الحجة النونية للقالب كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | يُهيّء مثالا جديدا من الصنف [XmlSchemaComplexType](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | يُهيّء مثالا جديدا من الصنف [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | يُهيّء مثالا جديدا من الصنف [XmlSchemaType](../xmlschematype/). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## التعريفات النوعية

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى مثال من هذا الصنف. |

## ملاحظات



يجب تخصيص كائنات هذا الصنف فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء مثيلات لهذا النوع على المكدس أو باستخدام معامل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أعطال تأكيد. دائمًا ضع هذا الصنف داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. 

## راجع أيضًا

* الصنف [XmlSchemaType](../xmlschematype/)
* مساحة الاسم [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)