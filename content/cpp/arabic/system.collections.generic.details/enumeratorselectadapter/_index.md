---
title: EnumeratorSelectAdapter
second_title: مرجع API Aspose.Slides للغة C++
description: المُعدِّد يُستخدم بواسطة طريقة الامتداد IEnumerable.Select().
type: docs
weight: 79
url: /ar/system.collections.generic.details/enumeratorselectadapter/
---
## EnumeratorSelectAdapter فئة

المُعدِّد المستخدم بواسطة طريقة الامتداد IEnumerable.Select().

```cpp
template<typename Source,typename Result>class EnumeratorSelectAdapter : public System::Collections::Generic::IEnumerator<Result>
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| Source | نوع المصدر لعناصر المجموعة. |
| Result | نوع النتيجة لعناصر المجموعة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [IEnumerator](../../system.collections.generic/ienumerator/) * [AsVirtualizedIterator](../../system.collections.generic/ienumerator/asvirtualizediterator/)() | يجهّز المتكرّر لاستخدامه من قِبل فئة VirtualizedIterator. |
| System::Details::VirtualizedIteratorBase\<Result\> * [CloneIterator](./cloneiterator/)() const override |  |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../../system.collections.generic/ienumerator/current/)() const | يحصل على العنصر الحالي. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | لا يفعل شيئًا. |
|  [EnumeratorSelectAdapter](./enumeratorselectadapter/)([SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<Source\>\>, const [Func](../../system/func/)\<Source, Result\>\&) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلّد مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا للمعيار IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلّد مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا للمعيار IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Result\> [get_Current](./get_current/)() const override | يحصل على العنصر الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [IEnumerator](../../system.collections.generic/ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../../system.collections.generic/ienumerator/incrementiterator/)() override | يحرك المتكرّر خطوة إلى الأمام. |
| void [InitializeIterator](../../system.collections.generic/ienumerator/initializeiterator/)() override | يقوم بأول استدعاء [MoveNext()](../../system.collections.generic/ienumerator/movenext/) ويجهّز كائن المُعدِّد لاستخدامه من قبل VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموضّح بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| void [MarkOwnedByVirtualizedIterator](../../system.collections.generic/ienumerator/markownedbyvirtualizediterator/)() | يعلّم المُعدِّد المملوك للمتكرّر الظاهري. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| **bool** [MoveNext](./movenext/)() override | يحوّل المُعدِّد إلى العنصر التالي. إذا لم يكن هناك عنصر مُشار إليه مسبقًا، يضبط المرجع إلى أول عنصر متاح. إذا وصل إلى نهاية الحاوية، لا يفعل شيئًا. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [Reset](./reset/)() override | يعيد ضبط المُعدِّد إلى الوضع قبل العنصر الأول. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب الـ n't مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ تركيب C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~IEnumerator](../../system.collections.generic/ienumerator/~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [IEnumerator](../../system.collections.generic/ienumerator/)
* النطاق [System::Collections::Generic::Details](../)
* المكتبة [Aspose.Slides](../../)