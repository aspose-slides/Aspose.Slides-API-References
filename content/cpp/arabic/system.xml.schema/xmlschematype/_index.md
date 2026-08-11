---
title: XmlSchemaType
second_title: مرجع API لـ Aspose.Slides للغة C++
description: الفئة الأساسية لجميع الأنواع البسيطة والمعقدة.
type: docs
weight: 911
url: /ar/system.xml.schema/xmlschematype/
---
## XmlSchemaType فئة


الفئة الأساسية لجميع الأنواع البسيطة والمعقدة.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | يعيد خاصية **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](./get_baseschematype/)() | يعيد نوع كائن ما بعد التجميع أو نوع البيانات المدمج XML [Schema](../) Definition Language (XSD) ، أو العنصر simpleType ، أو العنصر complexType. هذه قيمة infoset ما بعد تجميع المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\> [get_BaseXmlSchemaType](./get_basexmlschematype/)() | يعيد القيمة ما بعد التجميع للنوع الأساسي لهذا نوع المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](./get_datatype/)() | يعيد القيمة ما بعد التجميع لنوع البيانات للنوع المعقد. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](./get_derivedby/)() | يعيد معلومات ما بعد التجميع حول كيفية اشتقاق هذا العنصر من نوعه الأساسي. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | يعيد السمة النهائية للاشتقاق النوع الذي يشير إلى ما إذا كان يُسمح بمزيد من الاشتقاقات. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | يعيد تفسير ما بعد التجميع للقيمة [XmlSchemaType::get_Final](./get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | يعيد معرف السلسلة. |
| virtual **bool** [get_IsMixed](./get_ismixed/)() | يعيد قيمة تشير إلى ما إذا كان لهذا النوع نموذج محتوى مختلط. هذا الاستدعاء صالح فقط في النوع المعقد. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | يعيد رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | يعيد موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| [String](../../system/string/) [get_Name](./get_name/)() | يعيد اسم النوع. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | يعيد XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | يعيد العنصر الأب لهذا [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | يعيد الاسم المؤهل للنوع المبني من السمة **Name** لهذا النوع. هذه قيمة ما بعد تجميع المخطط. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | يعيد موقع المصدر للملف الذي حمّل المخطط. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | يعيد XmlTypeCode للنوع. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | يعيد السمات المؤهلة التي لا تنتمي إلى مساحة اسم الهدف الحالية للمخطط. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | يعيد [XmlSchemaComplexType](../xmlschemacomplextype/) الذي يمثل النوع المعقد المدمج للنوع المعقد المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يعيد [XmlSchemaComplexType](../xmlschemacomplextype/) الذي يمثل النوع المعقد المدمج للنوع المعقد المحدد بالاسم المؤهل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | يعيد [XmlSchemaSimpleType](../xmlschemasimpletype/) الذي يمثل النوع البسيط المدمج للنوع البسيط المحدد بالاسم المؤهل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | يعيد [XmlSchemaSimpleType](../xmlschemasimpletype/) الذي يمثل النوع البسيط المدمج للنوع البسيط المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر معامل C# 'is'. |
| static **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يعيد قيمة تشير إلى ما إذا كان نوع المخطط المشتق المحدد مشتقًا من نوع المخطط الأساسي المحدد. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع البُنى الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح ببناء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل التعيين. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح ببناء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | يضبط خاصية **annotation**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يضبط السمة النهائية للاشتقاق النوع الذي يشير إلى ما إذا كان يُسمح بمزيد من الاشتقاقات. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | يضبط معرف السلسلة. |
| virtual void [set_IsMixed](./set_ismixed/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان لهذا النوع نموذج محتوى مختلط. هذا الاستدعاء صالح فقط في النوع المعقد. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | يضبط رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | يضبط موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | يضبط اسم النوع. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | يضبط XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | يضبط العنصر الأب لهذا [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | يضبط موقع المصدر للملف الذي حمّل المخطط. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | يضبط السمات المؤهلة التي لا تنتمي إلى مساحة اسم الهدف الحالية للمخطط. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n'th كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | يهيئ نسخة جديدة من الفئة [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaType](./xmlschematype/)() | يهيئ نسخة جديدة من الفئة [XmlSchemaType](./). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع البُنى الداخلية. |
## تعريفات النوع

| تعريف النوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار للمؤشر المشترك إلى نسخة من هذه الفئة. |
## ملاحظات

يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخ من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. 

## انظر أيضًا

* فئة [XmlSchemaAnnotated](../xmlschemaannotated/)
* نطاق [System::Xml::Schema](../)
* مكتبة [Aspose.Slides](../../)