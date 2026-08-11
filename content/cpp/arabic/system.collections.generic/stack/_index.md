---
title: Stack
second_title: مرجع API Aspose.Slides للغة C++
description: إعلان مسبق لفئة Stack.
type: docs
weight: 599
url: /ar/system.collections.generic/stack/
---
## فئة Stack

[Stack](./) فئة إعلان مسبق.

```cpp
template<typename T>class Stack : public System::Collections::Generic::IEnumerable<T>
```

### معلمات القالب

| Parameter | الوصف |
| --- | --- |
| T | نوع العنصر. |
## الطرق

| Method | الوصف |
| --- | --- |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | يضع العناصر في المكدس. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | يحصل على مكرر يشير إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المكرر لتغيير الكائن المرجعي لأن [GetEnumerator()](../ienumerable/getenumerator/) يُعيد نسخة من الكائن من النوع T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | يحصل على مكرر يشير إلى العنصر الأول (إن وجد) في النسخة المؤهلة بـ const من المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | يحصل على مكرر يشير إلى العنصر الأول المؤهل بـ const (إن وجد) في المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | يحصل على مكرر يشير مباشرةً بعد آخر عنصر مؤهل بـ const (إن وجد) في المجموعة. |
| virtual void [Clear](./clear/)() | يحذف جميع العناصر من المكدس. |
| virtual **bool** [Contains](./contains/)(const T&) const | يفحص ما إذا كان العنصر المحدد موجودًا في الحاوية؛ يستخدم المشغل == للمقارنة. |
| [stack_t](./stack_t/)& [data](./data/)() | مُوصل إلى بنية البيانات الداخلية. |
| const [stack_t](./stack_t/)& [data](./data/)() const | مُوصل إلى بنية البيانات الداخلية. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | يحصل على مكرر يشير مباشرةً بعد آخر عنصر (إن وجد) في المجموعة. لا يمكن استخدام هذا المكرر لتغيير الكائن المرجعي لأن [GetEnumerator()](../ienumerable/getenumerator/) يُعيد نسخة من الكائن من النوع T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | يحصل على مكرر يشير مباشرةً بعد آخر عنصر (إن وجد) في النسخة المؤهلة بـ const من المجموعة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | لأغراض داخلية فقط. |
| virtual int [get_Count](./get_count/)() const | يحصل على عدد العناصر في المكدس. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المراجع المرتبط بالكائن. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | يحصل على مكرر للتجول عبر المكدس الحالي. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر اتصال C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | يطبق دالة تراكم على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تحقق شرطًا. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | يحدد ما إذا كان هناك أي عنصر في التسلسل أو يحقق شرطًا. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب متوسط تسلسل القيم الرقمية. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | يحسب متوسط تسلسل القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من تسلسل الإدخال. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | يدمج تسلسلين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يرجع عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | يرجع عدد العناصر في التسلسل التي تحقق الشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يرجع العنصر في الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يرجع العنصر في الفهرس المحدد في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)() | يرجع أول عنصر في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | يرجع أول عنصر في التسلسل الذي يحقق الشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يرجع أول عنصر في التسلسل، أو القيمة الافتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | يرجع أول عنصر في التسلسل الذي يحقق شرطًا أو القيمة الافتراضية إذا لم يُعثر على عنصر كهذا. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | يقوم بتجميع عناصر التسلسل. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | يقوم بتجميع عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يرجع آخر عنصر في التسلسل. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يرجع آخر عنصر في التسلسل، أو القيمة الافتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | ينفذ دالة تحويل على كل عنصر من تسلسل عام ويُعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | ينفذ دالة تحويل على كل عنصر من تسلسل عام ويُعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | يفلتر عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | يرتب عناصر التسلسل تصاعديًا وفق قيم المفتاح التي يحددها keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | يرتب عناصر التسلسل تنازليًا وفق قيم المفتاح التي يحددها keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب العناصر في التسلسل. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | يحوّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | يحوّل كل عنصر من التسلسل إلى شكل جديد باستخدام فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | يُسقط كل عنصر من التسلسل ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتالية من بداية التسلسل ويُعيد البقية. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يرجع عددًا محددًا من العناصر المتتالية من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | يفلتر تسلسلًا بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن إنشاء نسخ من الفئات الفرعية. |
| T [Peek](./peek/)() | يحصل على العنصر من قمة المكدس، لكنه يبقى في المكدس. |
| T [Pop](./pop/)() | يحصل على العنصر من قمة المكدس. |
| void [Push](./push/)(const T&) | يضع عنصرًا في قمة المكدس. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | يقارن كائن نوع قيم بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد الإشارات المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد الإشارات المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عدد الإشارات المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [Stack](./stack/)() | ينشئ مكدسًا فارغًا. |
| [Stack](./stack/)(int) | ينشئ مكدسًا فارغًا. |
| [Stack](./stack/)([IEnumerablePtr](./ienumerableptr/)) | منشئ نسخ. |
| virtual [ArrayPtr](../../system/arrayptr/)<T> [ToArray](./toarray/)() | يقوم بتحويل المكدس إلى مصفوفة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | يحصل على تنفيذ مكرّر begin const للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | يحصل على تنفيذ مكرّر begin للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | يحصل على تنفيذ مكرّر end const للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeEndIterator](./virtualizeenditerator/)() override | يحصل على تنفيذ مكرّر end للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد الإشارات الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد الإشارات الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## تعريفات النوع

| Typedef | الوصف |
| --- | --- |
| [ValueType](./valuetype/) | نوع القيمة. |
| [stack_t](./stack_t/) | نوع البيانات الأساسي. |
| [IEnumerablePtr](./ienumerableptr/) | مجموعة تحتوي على عناصر من نفس النوع. |
| [IEnumeratorPtr](./ienumeratorptr/) | نوع **Enumerator**. |

## ملاحظات

[Stack](./) فئة تغلف std::list. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../../system/makeobject/). لا تنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيسبّب أخطاء وقت التشغيل و/أو أخطاء تأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
#include <system/collections/stack.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &stack)
{
  for (const auto item: stack)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // إنشاء كائن فئة Stack.
  auto stack = MakeObject<Stack<int>>();

  // ملء المكدس.
  stack->Push(1);
  stack->Push(2);
  stack->Push(3);

  // طباعة العنصر الأخير من المكدس. طريقة Peek لا تزيل العنصر من المكدس.
  std::cout << stack->Peek() << std::endl;
  PrintItems(stack);

  // طباعة العنصر الأخير من المكدس. طريقة Pop تزيل العنصر من المكدس.
  std::cout << stack->Pop() << std::endl;
  PrintItems(stack);

  return 0;
}
/*
هذا المثال البرمجي ينتج الإخراج التالي:
3
3 2 1
3
2 1
*/
```

## انظر أيضاً

* الفئة [IEnumerable](../ienumerable/)
* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)