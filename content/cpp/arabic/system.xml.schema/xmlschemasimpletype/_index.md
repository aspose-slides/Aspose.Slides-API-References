---
title: XmlSchemaSimpleType
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل عنصر simpleType للمحتوى البسيط من XML Schema كما هو محدد من قبل منظمة الويب العالمية (W3C). تُعرّف هذه الفئة نوعًا بسيطًا. يمكن للأنواع البسيطة تحديد المعلومات والقيود لقيمة السمات أو العناصر ذات المحتوى النصي فقط.
type: docs
weight: 833
url: /ar/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType فئة


Represents the **simpleType** element for simple content from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class defines a simple type. Simple types can specify information and constraints for the value of attributes or elements with text-only content.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | يرجع الخاصية **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | يرجع نوع كائن ما بعد التجميع أو نوع البيانات المدمج XML [Schema](../) Definition Language (XSD)، عنصر simpleType، أو عنصر complexType. هذه قيمة مجموعة معلومات ما بعد تجميع المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | يرجع قيمة ما بعد التجميع لنوع الأساس لهذا النوع من المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\> [get_Content](./get_content/)() | يرجع أحد [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/) أو [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) أو [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | يرجع قيمة ما بعد التجميع لنوع البيانات للنوع المعقد. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | يرجع معلومات ما بعد التجميع حول كيفية اشتقاق هذا العنصر من نوعه الأساسي. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | يرجع السمة النهائية لاشتقاق النوع التي تشير إلى ما إذا كان يُسمح بالاشتقاقات الإضافية. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | يرجع تفسير ما بعد التجميع للقيمة [XmlSchemaType::get_Final](../xmlschematype/get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | يرجع معرّف السلسلة. |
| virtual **bool** [get_IsMixed](../xmlschematype/get_ismixed/)() | يرجع قيمة تشير إلى ما إذا كان لهذا النوع نموذج محتوى مختلط. هذا الاستدعاء صالح فقط في نوع معقد. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | يرجع رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | يرجع موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | يرجع اسم النوع. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | يرجع XmlSerializerNamespaces لاستخدامها مع كائن المخطط هذا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | يرجع الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | يرجع الاسم المؤهل للنوع المبني من سمة **Name** لهذا النوع. هذه قيمة ما بعد تجميع المخطط. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | يرجع موقع المصدر للملف الذي حمَّل المخطط. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | يرجع XmlTypeCode للنوع. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | يرجع السمات المؤهلة التي لا تنتمي إلى مساحة الاسم الهدف للمخطط الحالي. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | يرجع [XmlSchemaComplexType](../xmlschemacomplextype/) الذي يمثل النوع المعقد المدمج للنوع المعقد المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يرجع [XmlSchemaComplexType](../xmlschemacomplextype/) الذي يمثل النوع المعقد المدمج للنوع المعقد المحدد بالاسم المؤهل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يرجع [XmlSchemaSimpleType](./) الذي يمثل النوع البسيط المدمج للنوع البسيط المحدد بالاسم المؤهل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | يرجع [XmlSchemaSimpleType](./) الذي يمثل النوع البسيط المدمج للنوع البسيط المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثلاً للنوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يرجع قيمة تشير إلى ما إذا كان نوع المخطط المستمد المحدد مشتقًا من نوع المخطط الأساسي المحدد. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يتهيئ كائنًا جديدًا ويمكّن بناء النسخ للأنواع الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يتهيئ كائنًا جديدًا ويمكّن بناء النسخ للأنواع الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | يضبط الخاصية **annotation**. |
| void [set_Content](./set_content/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\>\&) | يضبط أحد [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/) أو [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) أو [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يضبط السمة النهائية لاشتقاق النوع التي تشير إلى ما إذا كان يُسمح بالاشتقاقات الإضافية. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | يضبط معرّف السلسلة. |
| virtual void [set_IsMixed](../xmlschematype/set_ismixed/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان لهذا النوع نموذج محتوى مختلط. هذا الاستدعاء صالح فقط في نوع معقد. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | يضبط رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | يضبط موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | يضبط اسم النوع. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | يضبط XmlSerializerNamespaces لاستخدامها مع كائن المخطط هذا. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | يضبط الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | يضبط موقع المصدر للملف الذي حمَّل المخطط. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | يضبط السمات المؤهلة التي لا تنتمي إلى مساحة الاسم الهدف للمخطط الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ تركيب C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | يُنشئ نسخة جديدة من الصنف [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaSimpleType](./xmlschemasimpletype/)() | يُنشئ نسخة جديدة من الصنف [XmlSchemaSimpleType](./). |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | يُنشئ نسخة جديدة من الصنف [XmlSchemaType](../xmlschematype/). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## الأنواع المُعرفة

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذا الصنف. |

## ملاحظات

يجب تخصيص كائنات هذا الصنف فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخ من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيتسبب في أخطاء وقت التشغيل و/أو أعطال التأكيد. احْطِ هذا الصنف دائمًا في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. 

## انظر أيضًا

* الصنف [XmlSchemaType](../xmlschematype/)
* النطاق [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)