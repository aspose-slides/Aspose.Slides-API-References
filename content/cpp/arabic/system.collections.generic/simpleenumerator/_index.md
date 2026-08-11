---
title: SimpleEnumerator
second_title: مرجع Aspose.Slides للـ C++ API
description: "فئة مكرّر (Iterator) للحاويات البسيطة التي تحتفظ بالعناصر مباشرةً باستخدام دالتي rbegin() و rend(). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، حيث سيتسبب ذلك في أخطاء تشغيلية و/أو عطل في التأكيدات. يجب دائمًا تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريرها إلى الدوال كمعامل."
type: docs
weight: 508
url: /ar/system.collections.generic/simpleenumerator/
---
## SimpleEnumerator فئة

Iterator فئة للحاويات البسيطة التي تحتفظ بالعناصر مباشرةً باستخدام دالتي rbegin() و rend(). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال في التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
template<typename Container,typename Element>class SimpleEnumerator : public System::Collections::Generic::BaseEnumerator<Container, typename Container::value_type>
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| Container | نوع الحاوية للتكرار عبرها. |
| Element | نوع العنصر. |

## الطرق

| Method | Description |
| --- | --- |
| [IEnumerator](../ienumerator/) * [AsVirtualizedIterator](../ienumerator/asvirtualizediterator/)() | يجهز المُتكرّر للاستخدام بواسطة فئة VirtualizedIterator. |
|  [BaseEnumerator](../baseenumerator/baseenumerator/)(const [Object::ptr](../../system/object/ptr/)\&, Container\&) | يهيّء المُتكرّر. |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | يستنسخ المُتكرّر الحالي. |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../ienumerator/current/)() const | يحصل على العنصر الحالي. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | لا يفعل شيئًا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أن IEC 60559:1989 تقول إن NaN لا تساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أن IEC 60559:1989 تقول إن NaN لا تساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Element\> [get_Current](./get_current/)() const override | يحصل على العنصر “الحالي”. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن التجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [IEnumerator](../ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../ienumerator/incrementiterator/)() override | ينقل المُتكرّر خطوة إلى الأمام. |
| void [InitializeIterator](../ienumerator/initializeiterator/)() override | يُجري أول استدعاء [MoveNext()](../ienumerator/movenext/) ويجهز كائن المُعداد للاستخدام بواسطة VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. نظير معامل C# “is”. |
| **bool** [IsValid](../baseenumerator/isvalid/)() const | يتحقق ما إذا تم استدعاء [MoveNext()](../baseenumerator/movenext/) ولم يتم الوصول إلى النهاية. |
| void [Lock](../../system/object/lock/)() | يطبّق بيان القفل C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| void [MarkOwnedByVirtualizedIterator](../ienumerator/markownedbyvirtualizediterator/)() | يعلّم المُعداد المملوك للمتكرّر الظاهري. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
| **bool** [MoveNext](../baseenumerator/movenext/)() override | زيادة على نمط المُعداد. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويسمح بنسخ بنية الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويسمح بنسخ بنية الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [Reset](../baseenumerator/reset/)() override | يعيد ضبط المُعداد للسماح بإعادة تعداد العناصر. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالب الـ nth إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [SimpleEnumerator](./simpleenumerator/)([Object::ptr](../../system/object/ptr/), Container\&) | ينشئ متكرّرًا بسيطًا. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبّق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبّق بيان إلغاء القفل C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~IEnumerator](../ienumerator/~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [BaseEnumerator](../baseenumerator/)
* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)