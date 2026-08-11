---
title: XmlSchemaTotalDigitsFacet
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل الجانب totalDigits من مخطط XML كما حددته مجموعة العمل العالمية للويب (W3C). يمكن استخدام هذه الفئة لتحديد قيد على عدد الأرقام التي يمكن إدخالها لقيمة عنصر simpleType. يجب أن تكون قيمة totalDigits عددًا صحيحًا موجبًا.
type: docs
weight: 898
url: /ar/system.xml.schema/xmlschematotaldigitsfacet/
---
## XmlSchemaTotalDigitsFacet فئة

يمثل الجانب **totalDigits** من XML [Schema](../) كما حددت مجموعة العمل العالمية [Web](../../system.web/) (W3C). يمكن استخدام هذه الفئة لتحديد قيد على عدد الأرقام التي يمكن إدخالها لقيمة عنصر **simpleType**. يجب أن تكون قيمة **totalDigits** عددًا صحيحًا موجبًا.

```cpp
class XmlSchemaTotalDigitsFacet : public System::Xml::Schema::XmlSchemaNumericFacet
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أن وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أن وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | يعيد خاصية **annotation**. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | يعيد معرّف السلسلة. |
| virtual **bool** [get_IsFixed](../xmlschemafacet/get_isfixed/)() | يعيد معلومات تشير إلى أن هذا الجانب ثابت. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | يعيد رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | يعيد موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | يعيد XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | يعيد الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | يعيد موقع المصدر للملف الذي حمّل المخطط. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | يعيد السمات المؤهلة التي لا تنتمي إلى مساحة الاسم الهدف للمخطط الحالي. |
| [String](../../system/string/) [get_Value](../xmlschemafacet/get_value/)() | يعيد صفة **value** للجانب. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة (hashing) الكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. تناظر معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويفعل إنشاء النسخ للفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويفعل إنشاء النسخ للفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | يضبط خاصية **annotation**. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | يضبط معرّف السلسلة. |
| virtual void [set_IsFixed](../xmlschemafacet/set_isfixed/)(**bool**) | يضبط معلومات تشير إلى أن هذا الجانب ثابت. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | يضبط رقم السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | يضبط موضع السطر في الملف الذي يشير إليه عنصر **schema**. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | يضبط XmlSerializerNamespaces لاستخدامه مع كائن المخطط هذا. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | يضبط الأصل لهذا [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | يضبط موقع المصدر للملف الذي حمّل المخطط. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | يضبط السمات المؤهلة التي لا تنتمي إلى مساحة الاسم الهدف للمخطط الحالي. |
| void [set_Value](../xmlschemafacet/set_value/)(const [String](../../system/string/)\&) | يضبط صفة **value** للجانب. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
|  [XmlSchemaFacet](../xmlschemafacet/xmlschemafacet/)() | يُهيّئ نسخة جديدة من الفئة [XmlSchemaFacet](../xmlschemafacet/). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | يُهيّئ نسخة جديدة من الفئة [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaTotalDigitsFacet](./xmlschematotaldigitsfacet/)() | يُهيّئ نسخة جديدة من الفئة [XmlSchemaTotalDigitsFacet](./). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## تعريفات الأنواع

| تعريف نوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار للمؤشر المشترك إلى نسخة من هذه الفئة. |

## ملاحظات

يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ أبداً نسخًا من هذا النوع على المكدس أو باستخدام المشغل new، إذ سيؤدي ذلك إلى أخطاء وقت تشغيل أو أعطال في التأكيد. دائمًا غلف هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. 

## أنظر أيضًا

* الفئة [XmlSchemaNumericFacet](../xmlschemanumericfacet/)
* مساحة الاسم [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)