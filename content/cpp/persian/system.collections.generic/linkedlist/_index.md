---
title: LinkedList
second_title: Aspose.Slides برای C++ مرجع API
description: اعلام پیش‌روی LinkedList.
type: docs
weight: 404
url: /fa/system.collections.generic/linkedlist/
---
## کلاس LinkedList

[LinkedList](./) forward declaration.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | Contained value type. |
## متدها

| متد | توضیح |
| --- | --- |
| void [Add](./add/)(const T\&) override | **عنصر** را به انتهای لیست اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | **عنصر** را پس از **node** در لیست اضافه می‌کند. |
| void [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | **newNode** را پس از **node** در لیست اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | **عنصر** را پیش از **node** در لیست اضافه می‌کند. |
| void [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | **newNode** را پیش از **node** در لیست اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddFirst](./addfirst/)(const T\&) | **عنصر** را به ابتدای لیست اضافه می‌کند. |
| void [AddFirst](./addfirst/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | **newNode** را به ابتدای لیست اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddLast](./addlast/)(const T\&) | **عنصر** را به انتهای لیست اضافه می‌کند. |
| void [AddLast](./addlast/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | **newNode** را به انتهای لیست اضافه می‌کند. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | یک **iterator** به اولین **عنصر** مجموعه برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | یک **iterator** به اولین **عنصر** مجموعه‌ای که const-qualified است برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | یک **iterator** به اولین عنصر const-qualified مجموعه برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | یک **iterator** برای عنصری const-qualified که وجود ندارد و پس از انتهای مجموعه است برمی‌گرداند. |
| void [Clear](./clear/)() override | تمام **عنصرها** را در لیست حذف می‌کند. |
| **bool** [Contains](./contains/)(const T\&) const override | بررسی می‌کند آیا **عنصر** در لیست موجود است. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | داده‌های کانتینر را در عناصر آرایه موجود کپی می‌کند. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | یک iterator معکوس به آخرین عنصر const-qualified مجموعه (اولین در جهت معکوس) برمی‌گرداند. |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | یک iterator معکوس برای عنصری که وجود ندارد و قبل از شروع مجموعه است برمی‌گرداند. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | یک iterator برای عنصر غیر موجود پس از انتهای مجموعه برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | یک iterator برای عنصر غیر موجود پس از انتهای مجموعه const-qualified برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [Find](./find/)(const T\&) const | جستجوی جهت جلو برای **عنصر** در لیست انجام می‌دهد. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [FindLast](./findlast/)(const T\&) const | جستجوی جهت معکوس برای **عنصر** در لیست انجام می‌دهد. |
| int [get_Count](./get_count/)() const override | تعداد **عنصرها** در لیست را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_First](./get_first/)() const | نشانگشتی به اولین **عنصر** در لیست برمی‌گرداند. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | بررسی می‌کند آیا مجموعه فقط‌خواندنی است. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_Last](./get_last/)() const | نشانگشتی به آخرین **عنصر** در لیست برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | شیئی را که مجموعه از طریق آن همگام‌سازی می‌شود برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() override | یک enumerator برای پیمایش [LinkedList](./) فعلی برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | سازندهٔ پیش‌فرض. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | سازندهٔ کپی. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | سازندهٔ جابجایی. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
|  [LinkedList](./linkedlist/)() | یک [LinkedList](./) خالی ایجاد می‌کند. |
|  [LinkedList](./linkedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>\&) | سازندهٔ کپی. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انباشتگر را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا تمام **عنصرها** یک دنباله شرطی را برآورده می‌کنند. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | تعیین می‌کند آیا یک دنباله شامل هرگونه **عنصر** است. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا هر عنصر از یک دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../ienumerable/linq_average/)() | میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین دنباله‌ای از مقادیر را محاسبه می‌کند که از طریق فراخوانی تابع تبدیل بر هر عنصر دنبالهٔ ورودی به دست می‌آیند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | دو دنباله را به‌هم می‌چسباند. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | تعیین می‌کند آیا دنباله شامل مقدار مشخصی است. |
| int [LINQ_Count](../ienumerable/linq_count/)() | تعداد **عنصرها** در دنباله را برمی‌گرداند (محاسبه شده با شمارش مستقیم). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد **عنصرها** در دنباله که شرط مشخص را برآورده می‌کنند را برمی‌گرداند. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | عنصری را که در اندیس مشخصی در دنباله قرار دارد برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | عنصری را که در اندیس مشخصی در دنباله قرار دارد برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)() | اولین **عنصر** دنباله را برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین **عنصر** دنباله که شرط مشخص را برآورده می‌کند را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | اولین **عنصر** دنباله یا مقدار پیش‌فرض اگر دنباله خالی باشد را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین **عنصر** دنباله که شرط را برآورده می‌کند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشد را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | آخرین **عنصر** دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | آخرین **عنصر** دنباله یا مقدار پیش‌فرض اگر دنباله خالی باشد را برمی‌گرداند. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و بیشترین مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و کمترین مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب صعودی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب نزولی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | ترتیب عناصر یک دنباله را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر از یک دنباله را به فرم جدیدی تبدیل می‌کند با درنظر گرفتن شاخص عنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | هر عنصر یک دنباله را پیش‌بینی می‌کند و دنباله‌های حاصل را در یک دنباله ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای دنباله پرش می‌کند و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای دنباله برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | یک آرایه از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | یک دنباله را بر اساس پیش‌شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی (cloning) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | اپراتور انتساب جابجایی. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | اپراتور انتساب جابجایی. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | یک iterator معکوس به آخرین عنصر مجموعه (اولین در جهت معکوس) برمی‌گرداند. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | یک iterator معکوس به آخرین عنصر مجموعه‌ای که const-qualified است (اولین در جهت معکوس) برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| **bool** [Remove](./remove/)(const T\&) override | اولین رخداد **عنصر** مشخص را از لیست حذف می‌کند. |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | node را از لیست حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [RemoveFirst](./removefirst/)() | اولین node را از لیست حذف می‌کند. |
| void [RemoveLast](./removelast/)() | آخرین node را از لیست حذف می‌کند. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | یک iterator معکوس برای عنصر غیر موجود قبل از شروع مجموعه برمی‌گرداند. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | یک iterator معکوس برای عنصر غیر موجود قبل از شروع مجموعه const-qualified برمی‌گرداند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام تمپلیت را به یک weak pointer تنظیم می‌کند (به جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری C# lock() را برای باز کردن پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | پیاده‌سازی iterator const آغاز برای کانتینر فعلی را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | پیاده‌سازی iterator آغاز برای کانتینر فعلی را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | پیاده‌سازی iterator const پایان برای کانتینر فعلی را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | پیاده‌سازی iterator پایان برای کانتینر فعلی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ weak reference را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ weak reference را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../icollection/~icollection/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [list_t](./list_t/) | Underlying data type. |
| [iterator](./iterator/) | Iterator type. |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
## توضیحات

کانتینر لیست لینک‌شده. یک wrapper بر روی std::list پیاده‌سازی می‌کند. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات assert خواهد شد. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید.

```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // یک نمونه از کلاس LinkedList ایجاد می‌کند.
  auto list = MakeObject<LinkedList<int>>();

  // لیست پیوندی را پر می‌کند.
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // موارد لیست پیوندی را چاپ می‌کند.
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
1 15 25 30
*/
```

## بخش‌های مرتبط

* کلاس [Object](../../system/object/)
* کلاس [ICollection](../icollection/)
* کلاس [Invalidatable](../../system.collections/invalidatable/)
* فضای نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)