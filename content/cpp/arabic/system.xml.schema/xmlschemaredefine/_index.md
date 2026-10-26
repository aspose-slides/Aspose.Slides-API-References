---
title: XmlSchemaRedefine
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل عنصر إعادة التعريف من مخطط XML كما هو محدد من قبل اتحاد الشبكة العالمية (W3C). يمكن استخدام هذه الفئة للسماح بأنواع بسيطة ومعقّدة، ومجموعات ومجموعات السمات من ملفات مخطط خارجية ليتم إعادة تعريفها في المخطط الحالي. يمكن أيضًا استخدام هذه الفئة لتوفير إصدار للعناصر في المخطط.
type: docs
weight: 755
url: /ar/system.xml.schema/xmlschemaredefine/
---
## فئة XmlSchemaRedefine

يمثِّل العنصر **redefine** من XML [Schema](../) كما هو موضح من قبل الاتحاد العالمي [Web](../../system.web/) (W3C). يمكن استخدام هذه الفئة للسماح بأنواع بسيطة ومعقدة، ومجموعات ومجموعات سمات من ملفات مخطط خارجية يتم إعادة تعريفها في المخطط الحالي. يمكن أيضًا استخدام هذه الفئة لتوفير النسخ للعناصر في المخطط.

```cpp
class XmlSchemaRedefine : public System::Xml::Schema::XmlSchemaExternal
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN مزدوجة متساويتين بالرغم من أن IEC 60559:1989 تُعلن أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN مزدوجة متساويتين بالرغم من أن IEC 60559:1989 تُعلن أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | يرجع [XmlSchemaObjectTable](../xmlschemaobjecttable/)، لجميع السمات في المخطط، الذي يحمل تفسير ما بعد التجميع لقيمة **AttributeGroups**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | يرجع [XmlSchemaObjectTable](../xmlschemaobjecttable/)، لجميع المجموعات في المخطط، الذي يحمل تفسير ما بعد التجميع لقيمة **Groups**. |
| [String](../../system/string/) [get_Id](../xmlschemaexternal/get_id/)() | يرجع معرّف السلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | يرجع مجموعة الفئات التالية: [XmlSchemaAnnotation](../xmlschemaannotation/)، [XmlSchemaAttributeGroup](../xmlschemaattributegroup/)، [XmlSchemaComplexType](../xmlschemacomplextype/)، [XmlSchemaSimpleType](../xmlschemasimpletype/)، و[XmlSchemaGroup](../xmlschemagroup/). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | يرجع رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | يرجع موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | يرجع XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | يرجع الأب لهذا [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [get_Schema](../xmlschemaexternal/get_schema/)() | يرجع [XmlSchema](../xmlschema/) للمخطط المشار إليه. |
| [String](../../system/string/) [get_SchemaLocation](../xmlschemaexternal/get_schemalocation/)() | يرجع موقع معرف المورد الموحد (URI) للمخطط، والذي يحدِّد للمعالج أين يقع المخطط فعليًا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | يرجع [XmlSchemaObjectTable](../xmlschemaobjecttable/)، لجميع الأنواع البسيطة والمعقدة في المخطط، الذي يحمل تفسير ما بعد التجميع لقيمة **SchemaTypes**. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | يرجع موقع المصدر للملف الذي حمَّل المخطط. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaexternal/get_unhandledattributes/)() | يرجع السمات المؤهلة التي لا تنتمي إلى مساحة اسم هدف المخطط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ما نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكِّن تجزئة الكائنات المخصَّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. ما نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. ما نظير عامل C# `is`. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ما نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكِّن استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخ. لا ينسخ شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكِّن نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكِّن نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Id](../xmlschemaexternal/set_id/)(const [String](../../system/string/)\&) | يضبط معرّف السلسلة. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | يضبط رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | يضبط موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | يضبط XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | يضبط أب لهذا [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Schema](../xmlschemaexternal/set_schema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | يضبط [XmlSchema](../xmlschema/) للمخطط المشار إليه. |
| void [set_SchemaLocation](../xmlschemaexternal/set_schemalocation/)(const [String](../../system/string/)\&) | يضبط موقع معرف المورد الموحد (URI) للمخطط، والذي يحدِّد للمعالج أين يقع المخطط فعليًا. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | يضبط موقع المصدر للملف الذي حمَّل المخطط. |
| void [set_UnhandledAttributes](../xmlschemaexternal/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | يضبط السمات المؤهلة التي لا تنتمي إلى مساحة اسم هدف المخطط. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيطة القالبية n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ما نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكِّن تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
|  [XmlSchemaExternal](../xmlschemaexternal/xmlschemaexternal/)() | يهيء نسخة جديدة من الفئة [XmlSchemaExternal](../xmlschemaexternal/). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | يهيء نسخة جديدة من الفئة [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaRedefine](./xmlschemaredefine/)() | يهيء نسخة جديدة من الفئة [XmlSchemaRedefine](./). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## التعريفات النوعية

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## ملاحظات

يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخ من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيسبب أخطاء تنفيذ أو أعطال في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدالات كمعامل.

## انظر أيضا

* الفئة [XmlSchemaExternal](../xmlschemaexternal/)
* النطاق [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)