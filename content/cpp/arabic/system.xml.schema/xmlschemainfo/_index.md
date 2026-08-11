---
title: XmlSchemaInfo
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل مجموعة المعلومات بعد التحقق من المخطط لعقدة XML تم التحقق منها.
type: docs
weight: 521
url: /ar/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo فئة


Represents the post-schema-validation infoset of a validated XML node.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات من نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات من نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُ considérer قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُ considérer قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | يعيد كائن XmlSchemaContentType الذي يتوافق مع نوع محتوى عقدة XML التي تم التحقق منها. |
| **bool** [get_IsDefault](./get_isdefault/)() override | يعيد قيمة تشير إلى ما إذا تم تعيين عقدة XML التي تم التحقق منها نتيجة لتطبيق القيمة الافتراضية أثناء تصديق مخطط XML [Schema](../) Definition Language (XSD). |
| **bool** [get_IsNil](./get_isnil/)() override | يعيد قيمة تشير إلى ما إذا كانت قيمة عقدة XML التي تم التحقق منها هي **nil**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_MemberType](./get_membertype/)() override | يعيد نوع المخطط الديناميكي لعقدة XML التي تم التحقق منها. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\> [get_SchemaAttribute](./get_schemaattribute/)() override | يعيد كائن [XmlSchemaAttribute](../xmlschemaattribute/) المترجم الذي يتوافق مع عقدة XML التي تم التحقق منها. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\> [get_SchemaElement](./get_schemaelement/)() override | يعيد كائن [XmlSchemaElement](../xmlschemaelement/) المترجم الذي يتوافق مع عقدة XML التي تم التحقق منها. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() override | يعيد نوع مخطط XML [Schema](../) Definition Language (XSD) الثابت لعقدة XML التي تم التحقق منها. |
| [XmlSchemaValidity](../xmlschemavalidity/) [get_Validity](./get_validity/)() override | يعيد قيمة XmlSchemaValidity لعقدة XML التي تم التحقق منها. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الوصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويفسح استنساخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويفسح استنساخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_ContentType](./set_contenttype/)([XmlSchemaContentType](../xmlschemacontenttype/)) | يضبط كائن XmlSchemaContentType الذي يتوافق مع نوع محتوى عقدة XML التي تم التحقق منها. |
| void [set_IsDefault](./set_isdefault/)(**bool**) | يضبط قيمة تشير إلى ما إذا تم تعيين عقدة XML التي تم التحقق منها نتيجة لتطبيق القيمة الافتراضية أثناء تصديق مخطط XML [Schema](../) Definition Language (XSD). |
| void [set_IsNil](./set_isnil/)(**bool**) | يضبط قيمة تشير إلى ما إذا كانت قيمة عقدة XML التي تم التحقق منها هي **nil**. |
| void [set_MemberType](./set_membertype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | يضبط نوع المخطط الديناميكي لعقدة XML التي تم التحقق منها. |
| void [set_SchemaAttribute](./set_schemaattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\&) | يضبط كائن [XmlSchemaAttribute](../xmlschemaattribute/) المترجم الذي يتوافق مع عقدة XML التي تم التحقق منها. |
| void [set_SchemaElement](./set_schemaelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\>\&) | يضبط كائن [XmlSchemaElement](../xmlschemaelement/) المترجم الذي يتوافق مع عقدة XML التي تم التحقق منها. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | يضبط نوع مخطط XML [Schema](../) Definition Language (XSD) الثابت لعقدة XML التي تم التحقق منها. |
| void [set_Validity](./set_validity/)([XmlSchemaValidity](../xmlschemavalidity/)) | يضبط قيمة XmlSchemaValidity لعقدة XML التي تم التحقق منها. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغير القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [XmlSchemaInfo](./xmlschemainfo/)() | يُهيئ مثيلًا جديدًا من الفئة [XmlSchemaInfo](./). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## تعريفات الأنواع

| تعريف نوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى مثيل من هذه الفئة. |

## ملاحظات

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## انظر أيضًا

* الفئة [IXmlSchemaInfo](../ixmlschemainfo/)
* النطاق [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)