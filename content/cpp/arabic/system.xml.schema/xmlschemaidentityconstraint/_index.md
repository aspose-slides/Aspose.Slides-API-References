---
title: XmlSchemaIdentityConstraint
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "فئة لقيود الهوية: العناصر key و keyref و unique."
type: docs
weight: 469
url: /ar/system.xml.schema/xmlschemaidentityconstraint/
---
## XmlSchemaIdentityConstraint فئة

فئة لقيود الهوية: العناصر **key**, **keyref**, و **unique**.

```cpp
class XmlSchemaIdentityConstraint : public System::Xml::Schema::XmlSchemaAnnotated
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا للمعيار IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة (double) بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا للمعيار IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | يعيد الخاصية **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Fields](./get_fields/)() | يعيد مجموعة الحقول التي تُطبق كعناصر فرعية لمحدد التعبير XML Path Language ([XPath](../../system.xml.xpath/)). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | يعيد المعرف النصي. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | يعيد رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | يعيد موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| [String](../../system/string/) [get_Name](./get_name/)() | يعيد اسم قيد الهوية. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | يعيد XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | يعيد الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | يعيد الاسم المؤهل لقيد الهوية، والذي يحمل تفسير ما بعد التجميع لقيمة **QualifiedName**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaXPath](../xmlschemaxpath/)\> [get_Selector](./get_selector/)() | يعيد عنصر **selector** لتعبير [XPath](../../system.xml.xpath/). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | يعيد موقع المصدر للملف الذي حمَّل المخطط. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | يعيد السمات المؤهلة التي لا تنتمي إلى مساحة الاسم الهدف للمخطط الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ تأثير قفل بيان C# lock(). يُستدعى مباشرة أو باستخدام كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | يضبط الخاصية **annotation**. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | يضبط المعرف النصي. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | يضبط رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | يضبط موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | يضبط اسم قيد الهوية. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | يضبط XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | يضبط الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Selector](./set_selector/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaXPath](../xmlschemaxpath/)\>\&) | يضبط عنصر **selector** لتعبير [XPath](../../system.xml.xpath/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | يضبط موقع المصدر للملف الذي حمَّل المخطط. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | يضبط السمات المؤهلة التي لا تنتمي إلى مساحة الاسم الهدف للمخطط الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الحجة النمطية رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). يُستدعى مباشرة أو باستخدام كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlSchemaIdentityConstraint](./xmlschemaidentityconstraint/)() | يُهيئ نسخة جديدة من الفئة [XmlSchemaIdentityConstraint](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | يُهيئ نسخة جديدة من الفئة [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## تعريفات الأنواع

| تعريف النوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## ملاحظات

يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تُنشئ أبدًا نسخًا من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبّب أخطاءً في وقت التشغيل و/أو أعطالًا في التأكيد. دائمًا ضع هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

## انظر أيضًا

* فئة [XmlSchemaAnnotated](../xmlschemaannotated/)
* مساحة الاسم [System::Xml::Schema](../)
* مكتبة [Aspose.Slides](../../)