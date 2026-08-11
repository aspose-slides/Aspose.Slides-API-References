---
title: XPathExpression
second_title: Aspose.Slides للغة C++ مرجع API
description: يوفر فئة ذات نوع محدد تمثل تعبير XPath مجمع.
type: docs
weight: 40
url: /ar/system.xml.xpath/xpathexpression/
---
## XPathExpression فئة

Provides a typed class that represents a compiled [XPath](../) expression.

```cpp
class XPathExpression : public System::Object
```

## طرق

| Method | Description |
| --- | --- |
| virtual void [AddSort](./addsort/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>) | عندما يتم تجاوزها في فئة مشتقة، تُرتب العقد التي اختارتها تعبير [XPath](../) وفقًا لكائن IComparer المحدد. |
| virtual void [AddSort](./addsort/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [XmlSortOrder](../xmlsortorder/), [XmlCaseOrder](../xmlcaseorder/), [String](../../system/string/), [XmlDataType](../xmldatatype/)) | عندما يتم تجاوزها في فئة مشتقة، تُرتب العقد التي اختارتها تعبير [XPath](../) وفقًا للمعلمات المقدمة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Clone](./clone/)() | عندما يتم تجاوزها في فئة مشتقة، تُرجع نسخة متماثلة من هذا [XPathExpression](./). |
| static [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Compile](./compile/)(const [String](../../system/string/)\&) | يُجمع تعبير [XPath](../) المحدد ويُرجع كائن [XPathExpression](./) يمثل تعبير [XPath](../). |
| static [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Compile](./compile/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&) | يُجمع تعبير [XPath](../) المحدد، مع كائن [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) المحدد لحل مساحة الاسم، ويُرجع كائن [XPathExpression](./) يمثل تعبير [XPath](../). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن IEC 60559:1989 تُعرّف NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين بالرغم من أن IEC 60559:1989 تُعرّف NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [String](../../system/string/) [get_Expression](./get_expression/)() | عندما يتم تجاوزها في فئة مشتقة، تحصل على تمثيل **string** للـ [XPathExpression](./). |
| virtual [XPathResultType](../xpathresulttype/) [get_ReturnType](./get_returntype/)() | عندما يتم تجاوزها في فئة مشتقة، تحصل على نوع النتيجة لتعبير [XPath](../). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل C# lock() . استدع مباشرة أو استخدم كائن الحراس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويفعل النسخ للأنواع الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويفعل النسخ للأنواع الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع قيم بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetContext](./setcontext/)([SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>) | عندما يتم تجاوزها في فئة مشتقة، تُحدد كائن [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) لاستخدامه في حل مساحة الاسم. |
| virtual void [SetContext](./setcontext/)([SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | عندما يتم تجاوزها في فئة مشتقة، تُحدد كائن [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) لاستخدامه في حل مساحة الاسم. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ فك قفل C# lock() . استدع مباشرة أو استخدم كائن الحراس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## أنواع تعريفية

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## انظر أيضًا

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)