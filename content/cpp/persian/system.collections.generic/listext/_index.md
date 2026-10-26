---
title: ListExt
second_title: مرجع API Aspose.Slides برای C++
description: کلاس عمومی List که رابط IListWrapper را پیاده‌سازی می‌کند
type: docs
weight: 443
url: /fa/system.collections.generic/listext/
---
## کلاس ListExt

کلاس عمومی [List](../list/) که رابط [IListWrapper](../../system.collections/ilistwrapper/) را پیاده‌سازی می‌کند

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## متدها

| Method | Description |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | ویژه C++. |
| void [Add](../list/add/)(const T\&) override | عنصری را به انتهای لیست اضافه می‌کند. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | عناصر را به لیست اضافه می‌کند؛ برای ترجمهٔ مقداردهی اولیه استفاده می‌شود. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | تمام عناصر از مجموعه (یا خود) را به انتهای لیست جاری اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | یک مرجع فقط-خواندنی به این مجموعه دریافت می‌کند. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | یک تکرارگر به اولین عنصر مجموعه دریافت می‌کند. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | یک تکرارگر به اولین عنصر مجموعهٔ const-صفتدار دریافت می‌کند. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | آیتم را در یک لیست مرتب جستجو می‌کند. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | آیتم را در یک لیست مرتب جستجو می‌کند. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | آیتم را در یک لیست مرتب جستجو می‌کند. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | یک تکرارگر به اولین عنصر const-صفتدار مجموعه دریافت می‌کند. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | یک تکرارگر برای یک عنصر const-صفتدار غیر‌موجود پس از انتهای مجموعه دریافت می‌کند. |
| void [Clear](../list/clear/)() override | تمام عناصر را حذف می‌کند. |
| **bool** [Contains](../list/contains/)(const T\&) const override | بررسی می‌کند آیا آیتم در لیست موجود است یا خیر. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | یک لیست از عناصر تبدیل‌شده به نوع متفاوت ایجاد می‌کند. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | عناصر لیست را در عناصر آرایه موجود کپی می‌کند. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | تمام عناصر را در عناصر آرایه موجود کپی می‌کند. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | عناصر را از ایندکس مشخص‌شده شروع کرده و در عناصر آرایه موجود کپی می‌کند. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | یک تکرارگر معکوس به آخرین عنصر const-صفتدار مجموعه (اولین در ترتیب معکوس) دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | پیاده‌سازی رابط [IListWrapper](../../system.collections/ilistwrapper/). |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | کمک‌کنندهٔ پیاده‌سازی [IListWrapper](../../system.collections/ilistwrapper/) برای انواع ارجاعی. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | کمک‌کنندهٔ پیاده‌سازی [IListWrapper](../../system.collections/ilistwrapper/) برای انواع مقدار. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | کمک‌کنندهٔ پیاده‌سازی [IListWrapper](../../system.collections/ilistwrapper/) برای سایر انواع. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | یک تکرارگر معکوس برای یک عنصر ‎const-صفتدار غیر‌موجود قبل از شروع مجموعه دریافت می‌کند. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | عملکرد دسترسی به ساختار دادهٔ زیرین. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | عملکرد دسترسی به ساختار دادهٔ زیرین. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | یک تکرارگر برای یک عنصر غیر‌موجود پس از انتهای مجموعه دریافت می‌کند. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | یک تکرارگر برای یک عنصر غیر‌موجود پس از انتهای مجموعهٔ ‎const-صفتدار دریافت می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور شبیه C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور شبیه C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | بررسی می‌کند آیا عنصری مطابق شرط خاص در لیست وجود دارد یا خیر. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | عنصری را مطابق شرط خاص جستجو می‌کند. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | عناصری را مطابق شرط خاص جستجو می‌کند. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | عنصری را مطابق شرط خاص جستجو می‌کند. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | عنصری را مطابق شرط خاص جستجو می‌کند. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | عنصری را مطابق شرط خاص جستجو می‌کند. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | آخرین عنصری مطابق شرط خاص را جستجو می‌کند. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | عملی را بر تمام عناصر لیست اعمال می‌کند. |
| int [get_Capacity](../list/get_capacity/)() const | ظرفیت فعلی لیست را دریافت می‌کند. |
| int [get_Count](../list/get_count/)() const override | تعداد عناصر در لیست فعلی را دریافت می‌کند. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | بررسی می‌کند آیا مجموعه اندازه ثابت دارد یا خیر. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | بررسی می‌کند آیا مجموعه فقط-خواندنی است یا خیر. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | شیئی که مجموعه از طریق آن همگام‌سازی می‌شود را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | یک شمارشگر برای تکرار بر عناصر لیست دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هاش‌سازی اشیاء سفارشی را فعال می‌کند. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | یک برش از لیست ایجاد می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | سازندهٔ پیش‌فرض. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | سازندهٔ کپی. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | سازندهٔ جابجایی. |
| T [idx_get](../list/idx_get/)(int) const override | عنصری را در موقعیت خاص دریافت می‌کند. |
| void [idx_set](../list/idx_set/)(int, T) override | عنصری را در موقعیت خاص تنظیم می‌کند. |
| int [IndexOf](../list/indexof/)(const T\&) const override | اولین ایندکس آیتم خاص را دریافت می‌کند. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | آیتم خاص را در لیست جستجو می‌کند. |
| void [Insert](../list/insert/)(int, const T\&) override | آیتمی را در موقعیت مشخص وارد می‌کند. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | بازه‌ای از داده‌ها را در موقعیت خاص وارد می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل اپراتور C# 'is'. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | برای شیء مشخص جستجو می‌کند و ایندکس صفر-پایهٔ آخرین وقوع آن را در کل لیست برمی‌گرداند. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | برای شیء مشخص جستجو می‌کند و ایندکس صفر-پایهٔ آخرین وقوع آن را در بازه‌ای از عناصر [List](../list/) که از اولین عنصر تا ایندکس مشخص گسترش می‌یابد، برمی‌گرداند. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | برای شیء مشخص جستجو می‌کند و ایندکس صفر-پایهٔ آخرین وقوع آن را در بازه‌ای از عناصر [List](../list/) که تعداد مشخصی عنصر دارد و در ایندکس مشخص پایان می‌یابد، برمی‌گرداند. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انباشته‌کننده را بر یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا تمام عناصر یک دنباله شرطی را برآورده می‌کنند. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | تعیین می‌کند آیا دنباله شامل هر عنصری است یا خیر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا هر عنصر از دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../ienumerable/linq_average/)() | میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین یک دنباله از مقادیر که با فراخوانی یک تابع تبدیل بر هر عنصر ورودی به‌دست می‌آیند، محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | دو دنباله را به‌هم می‌چسباند. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | تعیین می‌کند آیا دنباله شامل مقدار مشخصی است. |
| int [LINQ_Count](../ienumerable/linq_count/)() | تعداد عناصر دنباله را برمی‌گرداند (محاسبه‌شده از طریق شمارش مستقیم). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری که شرط مشخص را برآورده می‌شوند در دنباله برمی‌گرداند. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | عنصر را در ایندکس مشخصی از دنباله برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | عنصر را در ایندکس مشخصی از دنباله برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)() | اولین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصر دنباله‌ای که شرط مشخص را برآورده می‌کند، برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | اولین عنصر دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصر دنباله‌ای که شرط را برآورده می‌کند برمی‌گرداند، یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | آخرین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | آخرین عنصر دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی فراخوانی می‌کند و بیشترین مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی فراخوانی می‌کند و کمترین مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب صعودی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب نزولی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | ترتیب عناصر دنباله را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر دنباله را به فرم جدیدی تبدیل می‌کند با درگیر کردن ایندکس عنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | هر عنصر دنباله را به‌صورت پروژه‌کرده ترکیب می‌کند و توالی‌های حاصل را به یک توالی واحد می‌پیوندد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی عنصر متصل از شروع یک دنباله را حذف کرده و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی عنصر متصل را از شروع یک دنباله برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | یک آرایه از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | یک دنباله را بر اساس شرط مشخص فیلتر می‌کند. |
|  [List](../list/list/)() | لیست خالی ایجاد می‌کند. |
|  [List](../list/list/)(int) | لیستی با ظرفیت پیش‌تعریف‌شده ایجاد می‌کند. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | سازندهٔ کپی. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری C# lock(). مستقیم فراخوانی کنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازندهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازندهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | اپراتور انتساب جابجایی. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | اپراتور انتساب جابجایی. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | تابع دسترسی. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | تابع دسترسی. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | یک تکرارگر معکوس به آخرین عنصر مجموعه (اولین در ترتیب معکوس) دریافت می‌کند. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | یک تکرارگر معکوس به آخرین عنصر مجموعهٔ ‎const-صفتدار (اولین در ترتیب معکوس) دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| **bool** [Remove](../list/remove/)(const T\&) override | اولین نمونهٔ آیتم خاص را از لیست حذف می‌کند. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | تمام عناصر مطابق شرط خاص را حذف می‌کند. |
| void [RemoveAt](../list/removeat/)(int) override | آیتم را در موقعیت مشخص حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [RemoveRange](../list/removerange/)(int, int) | بخش (اسلایس) لیست را حذف می‌کند. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | یک تکرارگر معکوس برای یک عنصر ‎const-صفتدار غیر‌موجود قبل از شروع مجموعه دریافت می‌کند. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | یک تکرارگر معکوس برای یک عنصر ‎const-صفتدار غیر‌موجود قبل از شروع مجموعهٔ ‎const-صفتدار دریافت می‌کند. |
| void [Reverse](../list/reverse/)() | ترتیب عناصر کل لیست را معکوس می‌کند. |
| void [Reverse](../list/reverse/)(int, int) | ترتیب عناصر بخش (اسلایس) لیست را معکوس می‌کند. |
| void [set_Capacity](../list/set_capacity/)(int) | ظرفیت لیست را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | عناصر لیست را مرتب می‌کند. |
| void [Sort](../list/sort/)() | عناصر لیست را با استفاده از مقایسه‌گر پیش‌فرض مرتب می‌کند. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | عناصر بخش (اسلایس) لیست را مرتب می‌کند. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | عناصر لیست را مرتب می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | لیست را به آرایه تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| void [TrimExcess](../list/trimexcess/)() | ظرفیت لیست را به اندازهٔ آن تنظیم می‌کند. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | تعیین می‌کند آیا هر عنصر در مجموعه با شرایط تعریف‌شده توسط شرط مشخص هماهنگ است یا خیر. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی حالات باز کردن قفل C# lock(). مستقیم فراخوانی کنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | پیاده‌سازی تکرارگر const begin برای مخزن جاری را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | پیاده‌سازی تکرارگر begin برای مخزن جاری را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | پیاده‌سازی تکرارگر const end برای مخزن جاری را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | پیاده‌سازی تکرارگر end برای مخزن جاری را دریافت می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../icollection/~icollection/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعاریف نوع

| نوع‌تعریف | توضیح |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## موارد مرتبط

* کلاس [List](../list/)
* کلاس [IListWrapper](../../system.collections/ilistwrapper/)
* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)