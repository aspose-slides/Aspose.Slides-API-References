---
title: XmlSchema
second_title: Aspose.Slides للغة C++ مرجع API
description: تمثيل في الذاكرة لمخطط XML، كما هو محدد في اتحاد الويب العالمي (W3C) و .
type: docs
weight: 79
url: /ar/system.xml.schema/xmlschema/
---
## XmlSchema فئة

تمثيل في الذاكرة لمستند XML [Schema](../)، كما هو محدد في اتحاد الويب العالمي [Web](../../system.web/) (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) و [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## طرق

| Method | Description |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | يقوم بترجمة نموذج XML [Schema](../)[Object](../../system/object/) (SOM) إلى معلومات المخطط للتحقق من الصحة. يستخدم للتحقق من البنية النحوية والدلالية للـ SOM الذي تم بناءه برمجيًا. يتم تنفيذ فحص التحقق الدلالي أثناء التجميع. |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | يقوم بترجمة نموذج XML [Schema](../)[Object](../../system/object/) (SOM) إلى معلومات المخطط للتحقق من الصحة. يستخدم للتحقق من البنية النحوية والدلالية للـ SOM الذي تم بناءه برمجيًا. يتم تنفيذ فحص التحقق الدلالي أثناء التجميع. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعتبر NaNان متساويين رغم أنه وفقًا لمعيار IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعتبر NaNان متساويين رغم أنه وفقًا لمعيار IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | إرجاع الشكل للسمات المُعلنة في نطاق الهدف للمخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | إرجاع قيمة ما بعد تجميع المخطط لجميع مجموعات السمات العامة في المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | إرجاع قيمة ما بعد تجميع المخطط لجميع السمات في المخطط. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | إرجاع السمة **blockDefault** التي تحدد القيمة الافتراضية للسمة **block** على العنصر والأنواع المركبة في **targetNamespace** للمخطط. |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | إرجاع الشكل للعناصر المُعلنة في نطاق الهدف للمخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | إرجاع قيمة ما بعد تجميع المخطط لجميع العناصر في المخطط. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | إرجاع السمة **finalDefault** التي تحدد القيمة الافتراضية للسمة **final** على العناصر والأنواع المركبة في نطاق الهدف للمخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | إرجاع قيمة ما بعد تجميع المخطط لجميع المجموعات في المخطط. |
| [String](../../system/string/) [get_Id](./get_id/)() | إرجاع معرف السلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | إرجاع مجموعة المخططات المتضمنة والمستوردة. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | يشير إلى ما إذا كان المخطط قد تم تجميعه. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | إرجاع مجموعة عناصر المخطط في المخطط ويُستخدم لإضافة أنواع عناصر جديدة على مستوى عنصر **schema**. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | إرجاع رقم السطر في الملف الذي يُشير إليه عنصر **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | إرجاع موقع السطر في الملف الذي يُشير إليه عنصر **schema**. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | إرجاع XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | إرجاع قيمة ما بعد تجميع المخطط لجميع الترميزات في المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | إرجاع الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | إرجاع قيمة ما بعد تجميع المخطط لجميع أنواع المخطط في المخطط. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | إرجاع موقع المصدر للملف الذي حمَّل المخطط. |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | إرجاع معرف المورد الموحد (URI) لنطاق هدف المخطط. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | إرجاع السمات المؤهلة التي لا تنتمي إلى نطاق هدف المخطط. |
| [String](../../system/string/) [get_Version](./get_version/)() | إرجاع نسخة المخطط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | الحصول على بنية بيانات عداد المراجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | الحصول على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | التحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموضح بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات المشتقة. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | يقرأ XML [Schema](../) من الـ [IO::TextReader](../../system.io/textreader/) المزوَّد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | يقرأ XML [Schema](../) من الدفق المزوَّد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | يقرأ XML [Schema](../) من الـ [XmlReader](../../system.xml/xmlreader/) المزوَّد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقلل عداد المراجع المشتركة بالقيمة المحددة. |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | يضبط الشكل للسمات المُعلنة في نطاق الهدف للمخطط. |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يضبط السمة **blockDefault** التي تحدد القيمة الافتراضية للسمة **block** على العنصر والأنواع المركبة في **targetNamespace** للمخطط. |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | يضبط الشكل للعناصر المُعلنة في نطاق الهدف للمخطط. |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | يضبط السمة **finalDefault** التي تحدد القيمة الافتراضية للسمة **final** على العناصر والأنواع المركبة في نطاق الهدف للمخطط. |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | يضبط معرف السلسلة. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | يضبط رقم السطر في الملف الذي يُشير إليه عنصر **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | يضبط موقع السطر في الملف الذي يُشير إليه عنصر **schema**. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | يضبط XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | يضبط الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | يضبط موقع المصدر للملف الذي حمَّل المخطط. |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | يضبط معرف المورد الموحد (URI) لنطاق هدف المخطط. |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | يضبط السمات المؤهلة التي لا تنتمي إلى نطاق هدف المخطط. |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | يضبط نسخة المخطط. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يُعيّن الوسيط القالبي الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المراجع المشتركة ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | يكتب XML [Schema](../) إلى دفق البيانات المزوَّد. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | يكتب XML [Schema](../) إلى الـ Stream المزوَّد باستخدام [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) المحدد. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | يكتب XML [Schema](../) إلى الـ [IO::TextWriter](../../system.io/textwriter/) المزوَّد. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | يكتب XML [Schema](../) إلى الـ TextWriter المزوَّد. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | يكتب XML [Schema](../) إلى الـ [XmlWriter](../../system.xml/xmlwriter/) المزوَّد. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | يكتب XML [Schema](../) إلى الـ [XmlWriter](../../system.xml/xmlwriter/) المزوَّد. |
|  [XmlSchema](./xmlschema/)() | يقوم بتهيئة مثيل جديد من الفئة [XmlSchema](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | يقوم بتهيئة مثيل جديد من الفئة [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## حقول

| حقل | الوصف |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | مساحة اسم مثيل مخطط XML. هذا الحقل ثابت. |
| static [Namespace](./namespace/) | مساحة اسم مخطط XML. هذا الحقل ثابت. |

## تعريفات الأنواع

| تعريف نوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم بديل لمؤشر مشترك إلى مثيل من هذه الفئة. |

## ملاحظات

يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء مثيلات من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيسبب أخطاء في وقت التشغيل أو عطل في التأكيد. دائمًا قُم بلف هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. 

## انظر أيضًا

* فئة [XmlSchemaObject](../xmlschemaobject/)
* نطاق [System::Xml::Schema](../)
* مكتبة [Aspose.Slides](../../)