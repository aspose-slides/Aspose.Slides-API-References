---
title: List
second_title: مرجع API Aspose.Slides برای C++
description: اعلان پیش‌رو List.
type: docs
weight: 430
url: /fa/system.collections.generic/list/
---
## کلاس List

[List](./) اعلان پیشرو.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | Element type. |

## متدها

| Method | Description |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | مختص C++. |
| void [Add](./add/)(const T\&) override | عنصری را به انتهای لیست اضافه می‌کند. |
| void [AddInitializer](./addinitializer/)(int, const T *) | عناصری را به لیست اضافه می‌کند؛ در هنگام ترجمه‌ی مقداردهی‌ اولیه استفاده می‌شود. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | تمام عناصر از مجموعه (یا خود مجموعه) را به انتهای لیست جاری اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | یک مرجع فقط-خواندنی به این مجموعه برمی‌گرداند. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | یک تکرارگر به اولین عنصر مجموعه برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | یک تکرارگر به اولین عنصر از مجموعه‌ای که به صورت const تعریف شده است برمی‌گرداند. |
| int [BinarySearch](./binarysearch/)(const T\&) const | در یک لیست مرتب به دنبال آیتم می‌گردد. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | در یک لیست مرتب به دنبال آیتم می‌گردد. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | در یک لیست مرتب به دنبال آیتم می‌گردد. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | یک تکرارگر به اولین عنصر const-qualifed مجموعه برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | یک تکرارگر برای عنصر const-qualifed غیرموجود پشت انتهای مجموعه برمی‌گرداند. |
| void [Clear](./clear/)() override | تمام عناصر را حذف می‌کند. |
| **bool** [Contains](./contains/)(const T\&) const override | وجود آیتم در لیست را بررسی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | یک لیست از عناصری که به نوع متفاوتی تبدیل شده‌اند ایجاد می‌کند. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | عناصر لیست را در عناصر آرایه موجود کپی می‌کند. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | تمام عناصر را در عناصر آرایه موجود کپی می‌کند. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | عناصر را از ایندکس مشخص‌شده شروع کرده و در عناصر آرایه موجود کپی می‌کند. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | یک تکرارگر معکوس به آخرین عنصر const-qualifed مجموعه برمی‌گرداند (اولین در ترتیب معکوس). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | یک تکرارگر معکوس برای عنصر const-qualifed غیرموجود قبل از شروع مجموعه برمی‌گرداند. |
| [vector_t](./vector_t/)\& [data](./data/)() | تابع دسترسی به ساختار داده زیرین. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | تابع دسترسی به ساختار داده زیرین. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | یک تکرارگر برای عنصر غیرموجود پشت انتهای مجموعه برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | یک تکرارگر برای عنصر غیرموجود پشت انتهای مجموعه const-qualifed برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقدار، حتی NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقدار، حتی NaN نیست. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | وجود عنصر مطابق پیش‌شرط مشخص در لیست را بررسی می‌کند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای کاربردهای داخلی. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که مطابق پیش‌شرط خاص باشد. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عناصری می‌گردد که مطابق پیش‌شرط خاص باشند. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که مطابق پیش‌شرط خاص باشد. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که مطابق پیش‌شرط خاص باشد. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که مطابق پیش‌شرط خاص باشد. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال آخرین عنصر مطابق پیش‌شرط خاص می‌گردد. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | عمل را روی تمام عناصر لیست اعمال می‌کند. |
| int [get_Capacity](./get_capacity/)() const | ظرفیت فعلی لیست را برمی‌گرداند. |
| int [get_Count](./get_count/)() const override | تعداد عناصر در لیست فعلی را برمی‌گرداند. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | بررسی می‌کند که آیا مجموعه اندازه ثابت دارد. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | بررسی می‌کند که آیا مجموعه فقط-خواندنی است. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | شیئی را که مجموعه از طریق آن همگام‌سازی می‌شود برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | شمارنده‌ای برای پیمایش عناصر لیست برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هَش‌سازی اشیاء سفارشی را فعال می‌کند. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | یک تکه از لیست ایجاد می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | سازندهٔ پیش‌فرض. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | سازندهٔ کپی. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | سازندهٔ جابه‌جایی. |
| T [idx_get](./idx_get/)(int) const override | عنصر در موقعیت مشخص را برمی‌گرداند. |
| void [idx_set](./idx_set/)(int, T) override | عنصر در موقعیت مشخص را تنظیم می‌کند. |
| int [IndexOf](./indexof/)(const T\&) const override | اولین اندیس آیتم مشخص را برمی‌گرداند. |
| int [IndexOf](./indexof/)(const T\&, int) const | به دنبال آیتم مشخصی در لیست می‌گردد. |
| void [Insert](./insert/)(int, const T\&) override | آیتم را در موقعیت مشخص وارد می‌کند. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | محدودهٔ داده‌ها را در موقعیت مشخص وارد می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع تعریف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | آخرین وقوع شیء مشخص را در کل لیست پیدا می‌کند و اندیس صفر-محور آن را برمی‌گرداند. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | آخرین وقوع شیء مشخص را در بازهٔ عناصری که در [List](./) از اولین عنصر تا اندیس مشخص گسترش یافته است پیدا می‌کند و اندیس صفر-محور آن را برمی‌گرداند. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | آخرین وقوع شیء مشخص را در بازهٔ عناصری که در [List](./) شامل تعداد مشخصی عنصر است و در اندیس مشخص پایان می‌یابد پیدا می‌کند و اندیس صفر-محور آن را برمی‌گرداند. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع جمع‌کننده را بر روی توالی اعمال می‌کند. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا همهٔ عناصر توالی شرطی را برآورده می‌کنند. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | تعیین می‌کند که آیا توالی شامل هر عنصری است. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا هر عنصر توالی وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../ienumerable/linq_average/)() | میانگین توالی از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین توالی از مقادیری که با فراخوانی تابع تبدیل بر هر عنصر توالی ورودی به‌دست می‌آید را محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | دو توالی را به‌هم می‌پیوندد. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | تعیین می‌کند اگر توالی شامل مقدار مشخصی باشد. |
| int [LINQ_Count](../ienumerable/linq_count/)() | تعداد عناصر توالی را (محاسبه‌شده از شمارش مستقیم) برمی‌گرداند. |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری که شرط مشخص‌شده را برآورده می‌کنند برمی‌گرداند. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | عنصری را در ایندکس مشخص در توالی برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | عنصری را در ایندکس مشخص در توالی برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)() | اولین عنصر توالی را برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصری از توالی که شرط مشخص‌شده را برآورده می‌کند برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | اولین عنصر توالی یا مقدار پیش‌فرض اگر توالی خالی باشد را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصری از توالی که شرطی را برآورده می‌کند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصری از توالی را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصری از توالی را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | آخرین عنصر توالی را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | آخرین عنصر توالی یا مقدار پیش‌فرض اگر توالی خالی باشد را برمی‌گرداند. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | تابع تبدیل را بر هر عنصر توالی عمومی اعمال می‌کند و بیشینهٔ مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | تابع تبدیل را بر هر عنصر توالی عمومی اعمال می‌کند و کمینهٔ مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | عناصر توالی را بر پایهٔ نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر توالی را به ترتیب صعودی بر اساس مقادیر کلیدی که توسط keySelector انتخاب شده‌اند، مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر توالی را به ترتیب نزولی بر اساس مقادیر کلیدی که توسط keySelector انتخاب شده‌اند، مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | ترتیب عناصر توالی را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر توالی را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر توالی را به شکل جدیدی تبدیل می‌کند که اندیس عنصر را نیز در بر می‌گیرد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | هر عنصر توالی را پروژه می‌کند و توالی‌های حاصل را به یک توالی ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی عنصر متوالی از ابتدا را حذف می‌کند و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی عنصر متوالی از ابتدا را برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | آرایه‌ای از توالی ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | List<T> ای از توالی ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | توالی را بر پایهٔ پیش‌شرط مشخص فیلتر می‌کند. |
|  [List](./list/)() | لیست خالی ایجاد می‌کند. |
|  [List](./list/)(int) | لیست را با ظرفیت از پیش تعریف‌شده ایجاد می‌کند. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | سازندهٔ کپی. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری دستوری C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم یا با استفاده از شیء sentry [LockContext](../../system/lockcontext/) فراخوانی کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت سازندهٔ کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت سازندهٔ کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | عملگر انتساب جابه‌جایی. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | عملگر انتساب جابه‌جایی. |
| vector_t::reference [operator[]](./operator[]/)(int) | تابع دسترسی. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | تابع دسترسی. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | یک تکرارگر معکوس به آخرین عنصر مجموعه (اولین در ترتیب معکوس) برمی‌گرداند. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | یک تکرارگر معکوس به آخرین عنصر مجموعهٔ const-qualifed (اولین در ترتیب معکوس) برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع برای شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| **bool** [Remove](./remove/)(const T\&) override | اولین نمونهٔ آیتم مشخص را از لیست حذف می‌کند. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | تمام عناصری که پیش‌شرط خاص را برآورده می‌شوند حذف می‌کند. |
| void [RemoveAt](./removeat/)(int) override | آیتم را در موقعیت مشخص حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | مقدار مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| void [RemoveRange](./removerange/)(int, int) | یک تکه از لیست را حذف می‌کند. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | یک تکرارگر معکوس برای عنصر غیرموجود قبل از شروع مجموعه برمی‌گرداند. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | یک تکرارگر معکوس برای عنصر غیرموجود قبل از شروع مجموعهٔ const-qualifed برمی‌گرداند. |
| void [Reverse](./reverse/)() | ترتیب عناصر کل لیست را معکوس می‌کند. |
| void [Reverse](./reverse/)(int, int) | ترتیب عناصر تکهٔ لیست را معکوس می‌کند. |
| void [set_Capacity](./set_capacity/)(int) | ظرفیت لیست را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی n-ام را به اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | عناصر لیست را مرتب می‌کند. |
| void [Sort](./sort/)() | عناصر لیست را با مقایسه‌کننده پیش‌فرض مرتب می‌کند. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | تکه‌ای از لیست را مرتب می‌کند. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | عناصر لیست را مرتب می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | لیست را به آرایه تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| void [TrimExcess](./trimexcess/)() | ظرفیت لیست را طوری تنظیم می‌کند که با اندازهٔ آن منطبق باشد. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | تعیین می‌کند که آیا همهٔ عناصر مجموعه شرایط تعریف‌شده توسط پیش‌شرط مشخص را برآورده می‌کنند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم یا با استفاده از شیء sentry [LockContext](../../system/lockcontext/) فراخوانی کنید. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | پیاده‌سازی begin const iterator برای ظرف جاری را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | پیاده‌سازی begin iterator برای ظرف جاری را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | پیاده‌سازی end const iterator برای ظرف جاری را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | پیاده‌سازی end iterator برای ظرف جاری را برمی‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | تعداد ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تعداد ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../icollection/~icollection/)() | دست‌نشان. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | این نوع. |
| [BaseType](./basetype/) | نوع رابط. |
| [vector_t](./vector_t/) | نوع داده زیرین. |
| [iterator](./iterator/) | نوع تکرارگر. |
| [const_iterator](./const_iterator/) | نوع تکرارگر const. |
| [reverse_iterator](./reverse_iterator/) | نوع تکرارگر معکوس. |
| [const_reverse_iterator](./const_reverse_iterator/) | نوع تکرارگر معکوس const. |
| [IEnumerablePtr](./ienumerableptr/) | مخزنی که عناصر همان نوعی را که ما نگه می‌داریم، نگه می‌دارد. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** نوع. |

## توضیحات

[List](./) - wrapper around std::vector to be used in translated code. Requires operator == to be impemented for element type. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // ایجاد اولین لیست.
  auto list1 = MakeObject<List<int>>();

  // پر کردن اولین لیست.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // مرتب‌سازی اولین لیست.
  // آیتم‌های اولین لیست به این شکل خواهند بود: {-5, 1, 3, 8}
  list1->Sort();

  // حذف آیتم در ایندکس 2.
  // آیتم‌های اولین لیست به این شکل خواهند بود: {-5, 1, 8}
  list1->RemoveAt(2);

  // وارد کردن آیتم در ایندکس 1.
  // آیتم‌های اولین لیست به این شکل خواهند بود: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // ایجاد دومین لیست.
  auto list2 = MakeObject<List<int>>();

  // پر کردن دومین لیست.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // افزودن عناصر از دومین لیست به اولین لیست.
  list1->AddRange(list2);

  // چاپ آیتم‌های اولین لیست.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
- 5 15 1 8 10 20 30
*/
```

## موارد مرتبط

* کلاس [Object](../../system/object/)
* کلاس [IList](../ilist/)
* فضای نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)