---
title: Array
second_title: Aspose.Slides لـ C++ مرجع API
description: "فئة تمثل بنية بيانات المصفوفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدوال System::MakeArray() و System::MakeObject(). لا تقم أبدًا بإنشاء مثال لهذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبب أخطاء تشغيلية و/أو أعطال في العبارات الفرضية. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 14
url: /ar/system/array/
---
## فئة Array

الفئة التي تمثل بنية بيانات مصفوفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدوال [System::MakeArray()](../makearray/) و[System::MakeObject()](../makeobject/). لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء تشغيلية و/أو أعطال في التحقق. دائماً اغلف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر المصفوفة |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Add](./add/)(const T\&) override | غير مدعوم لأن المصفوفة التي يمثلها الكائن الحالي للقراءة فقط. |
| [Array](./array/)() | ينشئ مصفوفة فارغة. |
| [Array](./array/)(int, const T\&) | منشئ ملئ. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | منشئ ملئ. |
| [Array](./array/)(int, const T) | منشئ ملئ. |
| [Array](./array/)(**vector_t**\&&) | منشئ نقل. |
| [Array](./array/)(const **vector_t**\&) | منشئ نسخ. |
| [Array](./array/)(const std::vector\<Q\>\&) | ينشئ كائن [Array](./) ويملأه بالقيم المنقولة من كائن std::vector الذي يكون نوع قيمه هو نفسه **T** ولكن مختلف عن **UnderlyingType**. |
| [Array](./array/)(std::vector\<Q\>\&&) | ينشئ كائن [Array](./) ويملأه بالقيم المنقولة من كائن std::vector الذي يكون نوع قيمه هو نفسه **T** ولكن مختلف عن **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | ينشئ كائن [Array](./) ويملأه بالقيم من قائمة التهيئة المحددة التي تحتوي على عناصر من نوع **UnderlyingType**. |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | ينشئ كائن [Array](./) ويملأه بالقيم من المصفوفة المحددة التي تحتوي على عناصر من نوع **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | ينشئ كائن [Array](./) ويملأه بالقيم من قائمة التهيئة المحددة التي تحتوي على عناصر من نوع bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | يحوّل المصفوفة إلى مجموعة للقراءة فقط. |
| [iterator](./iterator/) [begin](./begin/)() | يعيد مكرر إلى أول عنصر في الحاوية. إذا كانت الحاوية فارغة، سيكون المكرر المعاد مساوياً لـ [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | يعيد مكرر إلى أول عنصر في الحاوية المؤهلة بالثابت. إذا كانت الحاوية فارغة، سيكون المكرر المعاد مساوياً لـ [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | يقوم ببحث ثنائي في المصفوفة المرتبة. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | غير مُنفّذ. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | يعيد مكرر إلى أول عنصر مؤهل بالثابت في الحاوية. إذا كانت الحاوية فارغة، سيكون المكرر المعاد مساوياً لـ [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | يعيد مكرر إلى العنصر التالي بعد آخر عنصر في الحاوية. هذا العنصر يعمل كعنصر نائب؛ محاولة الوصول إليه ينتج سلوكًا غير معرف. |
| void [Clear](./clear/)() override | غير مدعوم لأن المصفوفة التي يمثلها الكائن الحالي للقراءة فقط. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | يستبدل **count** قيمًا بدءًا من الفهرس **startIndex** في المصفوفة المحددة بالقيم الافتراضية. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | ينسخ المصفوفة. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | ينقل نطاقًا من العناصر من [System.Array](./) بدءًا من المصدر المحدد. |
| **bool** [Contains](./contains/)(const T\&) const override | يحدد ما إذا كان العنصر المحدد موجودًا في المصفوفة. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | ينشئ كائن [Array](./) جديدًا ويملأه بعناصر المصفوفة المحددة المحوّلة إلى نوع **OutputType** باستخدام المفوض المحول المحدد. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | ينشئ كائن [Array](./) جديدًا ويملأه بعناصر المصفوفة المحددة المحوّلة إلى نوع **OutputType** باستخدام كائن الدالة المحول المحدد. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | ينسخ العدد المحدد من العناصر من مصفوفة المصدر إلى مصفوفة الوجهة. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | ينسخ العدد المحدد من العناصر من عرض مصفوفة المصدر إلى مصفوفة الوجهة. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | ينسخ العدد المحدد من العناصر من مصفوفة المصدر إلى عرض مصفوفة الوجهة. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | ينسخ العدد المحدد من العناصر من عرض مصفوفة المصدر إلى عرض مصفوفة الوجهة. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | ينسخ العدد المحدد من العناصر من مصفوفة المصدر على المكدس إلى مصفوفة الوجهة. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | ينسخ العدد المحدد من العناصر من مصفوفة المصدر إلى مصفوفة الوجهة على المكدس. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | ينسخ العدد المحدد من العناصر من مصفوفة المصدر على المكدس إلى مصفوفة الوجهة على المكدس. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | ينسخ عددًا محددًا من العناصر من مصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في مصفوفة الوجهة. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | ينسخ عددًا محددًا من العناصر من عرض مصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في مصفوفة الوجهة. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | ينسخ عددًا محددًا من العناصر من مصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في عرض مصفوفة الوجهة. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | ينسخ عددًا محددًا من العناصر من عرض مصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في عرض مصفوفة الوجهة. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | ينسخ عددًا محددًا من العناصر من مصفوفة المصدر على المكدس بدءًا من الفهرس المحدد إلى الموضع المحدد في مصفوفة الوجهة. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | ينسخ عددًا محددًا من العناصر من مصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في مصفوفة الوجهة على المكدس. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | ينسخ عددًا محددًا من العناصر من مصفوفة المصدر على المكدس بدءًا من الفهرس المحدد إلى الموضع المحدد في مصفوفة الوجهة على المكدس. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | ينسخ عددًا محددًا من العناصر من عرض مصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في مصفوفة الوجهة على المكدس. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | ينسخ جميع عناصر المصفوفة الحالية إلى مصفوفة الوجهة المحددة. تُدرج العناصر في مصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة معامل arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | ينسخ جميع عناصر المصفوفة الحالية إلى مصفوفة الوجهة المحددة. تُدرج العناصر في مصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة معامل dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | ينسخ جميع عناصر المصفوفة الحالية إلى عرض مصفوفة الوجهة المحدد. تُدرج العناصر في عرض مصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة معامل dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | ينسخ عددًا محددًا من العناصر من المصفوفة الحالية بدءًا من الموضع المحدد إلى مصفوفة الوجهة المحددة. تُدرج العناصر في مصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة معامل dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | ينسخ عددًا محددًا من العناصر من المصفوفة الحالية بدءًا من الموضع المحدد إلى عرض مصفوفة الوجهة المحدد. تُدرج العناصر في عرض مصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة معامل dstIndex. |
| int [Count](./count/)() const | يعيد رقمًا يمثل إجمالي عدد جميع العناصر في جميع أبعاد المصفوفة. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | يعيد مكررًا عكسيًا إلى أول عنصر في الحاوية المعكوسة. وهو يقابل آخر عنصر في الحاوية غير المعكوسة. إذا كانت الحاوية فارغة، يكون المكرر المعاد مساوياً لـ [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | يعيد مكررًا عكسيًا إلى العنصر التالي بعد آخر عنصر في الحاوية المعكوسة. وهو يقابل العنصر الذي يسبق أول عنصر في الحاوية غير المعكوسة. هذا العنصر يعمل كعنصر نائب؛ محاولة الوصول إليه ينتج سلوكًا غير معرف. |
| **vector_t**\& [data](./data/)() | يعيد مرجعًا إلى بنية البيانات الداخلية المستخدمة لتخزين عناصر المصفوفة. |
| const **vector_t**\& [data](./data/)() const | يعيد مرجعًا ثابتًا إلى بنية البيانات الداخلية المستخدمة لتخزين عناصر المصفوفة. |
| vector_t::pointer [data_ptr](./data_ptr/)() | يعيد مؤشرًا خامًا إلى بداية المخزن الذاكري حيث تُخزن عناصر المصفوفة. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | يعيد مؤشرًا خامًا ثابتًا إلى بداية المخزن الذاكري حيث تُخزن عناصر المصفوفة. |
| [iterator](./iterator/) [end](./end/)() | يعيد مكررًا إلى العنصر التالي بعد آخر عنصر في الحاوية. هذا العنصر يعمل كعنصر نائب؛ محاولة الوصول إليه ينتج سلوكًا غير معرف. |
| [const_iterator](./const_iterator/) [end](./end/)() const | يعيد مكررًا إلى العنصر التالي بعد آخر عنصر في الحاوية المؤهلة بالثابت. هذا العنصر يعمل كعنصر نائب؛ محاولة الوصول إليه ينتج سلوكًا غير معرف. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNs متساوية بالرغم من أن IEC 60559:1989 تقول إن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة عدد عشري بنمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | يحدد ما إذا كان كائن [Array](./) المحدد يحتوي على عنصر يفي بمتطلبات الدالة الشرطية المحددة. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | يبحث عن أول عنصر في المصفوفة المحددة يحقق شروط الدالة الشرطية المحددة. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | يسترجع جميع العناصر التي تطابق الشروط المحددة بواسطة الدالة الشرطية المحددة. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | يبحث عن أول عنصر في المصفوفة المحددة يحقق شروط الدالة الشرطية المحددة. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | ينفّذ الإجراء المحدد على كل عنصر من المصفوفة المحددة. |
| int [get_Count](./get_count/)() const override | يرجع حجم المصفوفة. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | يتحقق مما إذا كانت المجموعة ذات حجم ثابت. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | يشير إلى ما إذا كانت المصفوفة للقراءة فقط. |
| **int32_t** [get_Length](./get_length/)() const override | يرجع عددًا صحيحًا 32-بت يمثل العدد الإجمالي لجميع العناصر في جميع أبعاد المصفوفة. |
| **int64_t** [get_LongLength](./get_longlength/)() const | يرجع عددًا صحيحًا 64-بت يمثل العدد الإجمالي لجميع العناصر في جميع أبعاد المصفوفة. |
| **int32_t** [get_Rank](./get_rank/)() const | غير مُنفّذ. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | يحصل على الكائن الذي يتم مزامنة المجموعة من خلاله. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | يرجع مؤشرًا إلى كائن **Enumerator** الذي يوفر واجهة IEnumerator لعناصر المصفوفة التي يمثلها الكائن الحالي. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| int [GetLength](./getlength/)(int) | يرجع عدد العناصر في البعد المحدد. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | يرجع عدد العناصر في البعد المحدد كعدد صحيح 64-بت. |
| int [GetLowerBound](./getlowerbound/)(int) const | يرجع الحد الأدنى للبعد المحدد. |
| size_t [GetSizeTLength](./getsizetlength/)() const | يرجع متغير std::size_t يمثل العدد الإجمالي لجميع العناصر في جميع أبعاد المصفوفة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | يرجع الحد الأعلى للبعد المحدد. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | منشئ افتراضي. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | منشئ نسخ. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | منشئ نقل. |
| T [idx_get](./idx_get/)(int) const override | يرجع العنصر عند الفهرس المحدد. |
| void [idx_set](./idx_set/)(int, T) override | يضبط القيمة المحددة كعنصر للمصفوة عند الفهرس المحدد. |
| int [IndexOf](./indexof/)(const T\&) const override | يحدد فهرس أول وقوع للعنصر المحدد في المصفوفة. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | يحدد فهرس أول وقوع للعنصر المحدد في المصفوفة. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | يحدد فهرس أول وقوع للعنصر المحدد في المصفوفة بدءًا من الفهرس المحدد. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | يحدد فهرس أول وقوع للعنصر المحدد في نطاق من عناصر المصفوفة المحددة بواسطة فهرس البداية وعدد العناصر في النطاق. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | يملأ المصفوفة التي يمثلها الكائن الحالي بالقيم من المصفوفة المحددة. |
| void [Initialize](./initialize/)() | يملأ المصفوفة بالكائنات التي تم إنشاؤها افتراضيًا من النوع **T**. |
| void [Insert](./insert/)(int, const T\&) override | غير مدعوم لأن المصفوفة التي يمثلها الكائن الحالي للقراءة فقط. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | يحدد فهرس آخر وقوع للعنصر المحدد في نطاق من عناصر المصفوفة المحددة بواسطة فهرس البداية وعدد العناصر في النطاق. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | يحدد فهرس آخر وقوع للعنصر المحدد في المصفوفة بدءًا من الفهرس المحدد. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | يحدد فهرس آخر وقوع للعنصر المحدد في المصفوفة. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | يطَبّق دالة تراكم على تسلسل. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تلبي شرطًا. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان أي عنصر من التسلسل موجودًا أو يحقق شرطًا. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | يحسب متوسط تسلسل القيم العددية. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | يحسب متوسط تسلسل القيم التي يتم الحصول عليها باستدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | يقوم بتحويل عناصر إلى النوع المحدد. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | يدمج تسلسلين. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | يرجع عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | يرجع عدد العناصر في التسلسل التي تلبي الشرط المحدد. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | يرجع العنصر عند فهرس محدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | يرجع العنصر عند فهرس محدد في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | يرجع العنصر الأول من التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | يرجع العنصر الأول من التسلسل الذي يفي بالشرط المحدد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | يرجع العنصر الأول من التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يرجع العنصر الأول من التسلسل الذي يفي بشرط ما أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | يقوم بتجميع عناصر التسلسل. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | يقوم بتجميع عناصر التسلسل. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | يرجع العنصر الأخير من التسلسل. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | يرجع العنصر الأخير من التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة العظمى الناتجة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويعيد أصغر قيمة ناتجة. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | يرشح عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | يرتب عناصر التسلسل تصاعديًا وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | يرتب عناصر التسلسل تنازليًا وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | يعكس ترتيب عناصر التسلسل. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | يحوّل عناصر التسلسل. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | يحوّل كل عنصر من التسلسل إلى صيغة جديدة باستخدام فهرس العنصر. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | يُسقط كل عنصر من التسلسل ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتالية من بداية التسلسل ويعيد الباقي. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | يرجع عددًا محددًا من العناصر المتتالية من بداية التسلسل. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | يفلتر تسلسلًا استنادًا إلى الدالة الشرطية المحددة. |
| void [Lock](../object/lock/)() | ينفّذ قفل statement lock() في C#. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | يجد أكبر عنصر في المصفوفة باستخدام [operator<()](../operator_less/) للمقارنة بين العناصر. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | يجد أصغر عنصر في المصفوفة باستخدام [operator<()](../operator_less/) للمقارنة بين العناصر. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح نسخ البنى الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح نسخ البنى الفرعية. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | عامل إسناد النقل. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | عامل إسناد النقل. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | يرجع عنصرًا عند الفهرس المحدد. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | يرجع عنصرًا عند الفهرس المحدد. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | يرجع مؤشرًا إلى أول عنصر في مصفوفة أحادية البعد. بالنسبة للمصفوفات متعددة الأبعاد النتيجة غير معرفة. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | يرجع مكرّرًا عكسيًا إلى أول عنصر في الحاوية المعكوسة. وهو يتطابق مع آخر عنصر في الحاوية غير المعكوسة. إذا كانت الحاوية فارغة، فإن المكرّر المُرجَع يساوي [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | يعيد مكرِّرًا عكسيًا إلى العنصر الأول في الحاوية المقلوبة. يتطابق مع العنصر الأخير في الحاوية غير المقلوبة. إذا كانت الحاوية فارغة، يكون المكرّر المُرجع مساويًا لـ [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصص لـ [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصص لـ [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| **bool** [Remove](./remove/)(const T\&) override | غير مدعوم لأن المصفوفة الممثَّلة بواسطة الكائن الحالي للقراءة فقط. |
| void [RemoveAt](./removeat/)(int) override | غير مدعوم لأن المصفوفة الممثلة بواسطة الكائن الحالي للقراءة فقط. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | يعيد مكرِّرًا عكسيًا إلى العنصر التالي للعنصر الأخير في الحاوية المقلوبة. يتطابق مع العنصر السابق للعنصر الأول في الحاوية غير المقلوبة. هذا العنصر يعمل كعنصر نائب، والمحاولة للوصول إليه تؤدي إلى سلوك غير معرف. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | يعيد مكرِّرًا عكسيًا إلى العنصر التالي للعنصر الأخير في الحاوية المقلوبة. يتطابق مع العنصر السابق للعنصر الأول في الحاوية غير المقلوبة. هذا العنصر يعمل كعنصر نائب، والمحاولة للوصول إليه تؤدي إلى سلوك غير معرف. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | يغيّر حجم المصفوفة المحددة إلى القيمة المحددة أو ينشئ مصفوفة جديدة بالحجم المحدد. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | يعكس العناصر في المصفوفة المحددة. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | يعكس نطاقًا من العناصر في المصفوفة المحددة. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يجعل المصفوفة تعامل المؤشرات المخزنة كضعيفة (إن كان ذلك قابلًا للتطبيق). |
| void [SetValue](./setvalue/)(const T\&, int) | يضبط قيمة العنصر في الفهرس المحدد. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لمؤشر المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | يقلل ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | يرتب العناصر في المصفوفة المحددة باستخدام المقارن الافتراضي. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | يرتب نطاقًا من العناصر في المصفوفة المحددة باستخدام المقارن الافتراضي. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | يرتب العناصر في المصفوفة المحددة باستخدام المقارن المحدد. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | غير مُنفَّذ. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | يرتب العناصر في المصفوفة المحددة باستخدام المقارنة المحددة. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | يرتب مصفوفتين إحداهما تحتوي على المفاتيح والأخرى على العناصر المقابلة، بناءً على قيم المصفوفة التي تحتوي على المفاتيح، حيث تُقارن عناصرها باستخدام العامل <. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | يرتب مصفوفتين إحداهما تحتوي على المفاتيح والأخرى على العناصر المقابلة، بناءً على قيم المصفوفة التي تحتوي على المفاتيح، حيث تُقارن عناصرها باستخدام المقارن الافتراضي. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | نظير لطريقة C# [Object.ToString()](../object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | يحدد ما إذا كانت جميع العناصر في المصفوفة المحددة تلبي الشروط المعرفة بواسطة الشرط المحدد. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفّذ بنية C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن المراقبة [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | يحصل على تنفيذ مكرِّر البداية للمؤشر الثابت للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | يحصل على تنفيذ مكرِّر البداية للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | يحصل على تنفيذ مكرِّر النهاية للقراءة فقط للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | يحصل على تنفيذ مكرِّر النهاية للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | يقلل عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | المدمر. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## التعريفات

| التعريف | الوصف |
| --- | --- |
| [ValueType](./valuetype/) | اسم بديل لنوع عناصر المصفوفة. |
| [UnderlyingType](./underlyingtype/) | اسم بديل للنمط المستخدم لتمثيل كل عنصر من المصفوة. |
| [EnumerablePtr](./enumerableptr/) | اسم بديل لنوع المؤشر المشترك الذي يشير إلى كائن IEnumerable يحتوي على عناصر من النوع **T**. |
| [EnumeratorPtr](./enumeratorptr/) | اسم بديل لنوع المؤشر المشترك الذي يشير إلى كائن IEnumerator يحتوي على عناصر من النوع **T**. |
| [iterator](./iterator/) | نوع المكرِّر. |
| [const_iterator](./const_iterator/) | نوع المكرِّر الثابت. |
| [reverse_iterator](./reverse_iterator/) | نوع المكرِّر العكسي. |
| [const_reverse_iterator](./const_reverse_iterator/) | نوع المكرِّر العكسي الثابت. |
## الملاحظات



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // إنشاء وتعبئة المصفوفة.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // طباعة عناصر المصفوفة.
  Print(arrayPtr);

  // فرز عناصر المصفوفة تصاعديًا.
  Array<int32_t>::Sort(arrayPtr);

  // طباعة عناصر المصفوفة.
  Print(arrayPtr);

  // طباعة عدد عناصر المصفوفة.
  std::cout << arrayPtr->get_Length() << std::endl;

  // طباعة فهرس العنصر الذي يساوي 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // تغيير حجم المصفوفة.
  Array<int32_t>::Resize(arrayPtr, 3);

  // طباعة عناصر المصفوفة.
  Print(arrayPtr);

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## انظر أيضًا

* الفئة [ArrayBase](../arraybase/)
* الفئة [IList](../../system.collections.generic/ilist/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)