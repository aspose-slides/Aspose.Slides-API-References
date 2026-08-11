---
title: XmlSchemaCollectionEnumerator
second_title: Aspose.Slides لـ C++ مرجع API
description: يدعم تكرارًا بسيطًا على مجموعة. لا يمكن توريث هذه الفئة.
type: docs
weight: 235
url: /ar/system.xml.schema/xmlschemacollectionenumerator/
---
## XmlSchemaCollectionEnumerator فئة

Supports a simple iteration over a collection. This class cannot be inherited.

```cpp
class XmlSchemaCollectionEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [IEnumerator](../../system.collections.generic/ienumerator/) * [AsVirtualizedIterator](../../system.collections.generic/ienumerator/asvirtualizediterator/)() | يجهز المتكرر للاستخدام بواسطة فئة VirtualizedIterator. |
| System::Details::VirtualizedIteratorBase\<[SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchema](../xmlschema/)\>\> * [CloneIterator](./cloneiterator/)() const override | ينسخ المتكرر الحالي. |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../../system.collections.generic/ienumerator/current/)() const | يحصل على العنصر الحالي. |
| void [Dispose](./dispose/)() override | لا يفعل شيئًا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\& [get_Current](./get_current/)() const override | يعيد [XmlSchema](../xmlschema/) الحالي في المجموعة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [IEnumerator](../../system.collections.generic/ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../../system.collections.generic/ienumerator/incrementiterator/)() override | ينقل المتكرر خطوة إلى الأمام. |
| void [InitializeIterator](../../system.collections.generic/ienumerator/initializeiterator/)() override | يقوم بالنداء الأول لـ [MoveNext()](../../system.collections.generic/ienumerator/movenext/) ويجهز كائن العداد للاستخدام بواسطة VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموضح بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| void [MarkOwnedByVirtualizedIterator](../../system.collections.generic/ienumerator/markownedbyvirtualizediterator/)() | يعلِّم العداد المملوك للمتكرر الافتراضي. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
| **bool** [MoveNext](./movenext/)() override | يتقدّم بالعداد إلى المخطط التالي في المجموعة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع البنى الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن بنية النسخ للفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن بنية النسخ للفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n على مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد قيمة عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| virtual  [~IEnumerator](../../system.collections.generic/ienumerator/~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع البنى الداخلية. |

## الأنواع المعرفية

| اختصار | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اختصار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## ملاحظات

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## راجع أيضًا

* فئة [IEnumerator](../../system.collections.generic/ienumerator/)
* مساحة الاسم [System::Xml::Schema](../)
* مكتبة [Aspose.Slides](../../)