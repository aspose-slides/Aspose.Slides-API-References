---
title: SortedList
second_title: مرجع API Aspose.Slides برای C++
description: "لیست مرتب که ساختار FlatMap را می‌پوشاند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 547
url: /fa/system.collections.generic/sortedlist/
---
## SortedList کلاس

لیست مرتب‌شده که ساختار FlatMap را می‌پوشاند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای بیان می‌شود. همواره این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان پارامتر استفاده کنید.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلید. |
| TValue | نوع مقدار. |

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | یک جفت کلید-مقدار را به مخزن اضافه می‌کند. |
| virtual void [Add](../icollection/add/)(const T&) | یک عنصر را به مجموعه اضافه می‌کند. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | دستیابی به دستگا که به اولین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این دستگا نمی‌تواند برای تغییر شیء مرجع استفاده شود زیرا [GetEnumerator()](../ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | دستیابی به دستگا که به اولین عنصر (در صورت وجود) نمونه با قابلیت const مجموعه اشاره می‌کند. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | دستیابی به دستگا که به اولین عنصر (در صورت وجود) با قابلیت const مجموعه اشاره می‌کند. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | دستیابی به دستگا که درست پس از آخرین عنصر با قابلیت const (در صورت وجود) مجموعه اشاره می‌کند. |
| virtual void [Clear](../icollection/clear/)() | تمام عناصر را از مجموعه حذف می‌کند. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | بررسی می‌کند که آیا عنصر در مجموعه وجود دارد یا نه. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | بررسی می‌کند که آیا مخزن شامل کلید است یا نه. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | محتویات دیکشنری را به عناصر آرایه موجود کپی می‌کند. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | دستیابی به دستگا برعکس که به آخرین عنصر با قابلیت const مجموعه اشاره می‌کند (اولین عنصر در جهت معکوس). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | دستیابی به دستگا برعکس برای یک عنصر غیرموجود با قابلیت const قبل از آغاز مجموعه. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | دستیابی به دستگا که درست پس از آخرین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این دستگا نمی‌تواند برای تغییر شیء مرجع استفاده شود زیرا [GetEnumerator()](../ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | دستیابی به دستگا که درست پس از آخرین عنصر (در صورت وجود) نمونه با قابلیت const مجموعه اشاره می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | فقط برای مقاصد داخلی. |
| int [get_Capacity](./get_capacity/)() const | ظرفیت فعلی لیست را دریافت می‌کند. |
| virtual int [get_Count](../icollection/get_count/)() const | تعداد عناصر موجود در مجموعه را دریافت می‌کند. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | بررسی می‌کند که آیا اندازه مجموعه ثابت است یا نه. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | بررسی می‌کند که آیا مجموعه فقط خواندنی است یا نه. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | بررسی می‌کند که آیا مخزن ایمن برای استفاده چندنخی است یا نه. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IList](../ilist/)\<TKey\>\> [get_Keys](./get_keys/)() const | به مجموعه کلیدها دسترسی می‌یابد. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | شیئی که مجموعه از طریق آن همگام‌سازی می‌شود را دریافت می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IList](../ilist/)\<TValue\>\> [get_Values](./get_values/)() const | به مجموعه مقادیر دسترسی می‌یابد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده‌ی ارجاع مرتبط با شیء را دریافت می‌کند. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | یک enumerator که از لیست فعلی عبور می‌کند را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | اگر یافت شد مقدار را برمی‌گرداند؛ در غیر این صورت **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | اگر یافت شد مقدار را برمی‌گرداند؛ در غیر این صورت **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | اگر یافت شد مقدار را برمی‌گرداند؛ در غیر این صورت **null**، که فقط برای انواع مرجع معنای دارد. |
|  [ICollection](../icollection/icollection/)() | سازنده پیش‌فرض. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | سازنده کپی. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | سازنده جابجایی. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | تابع دریافت‌کننده. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | تابع تنظیم‌کننده. |
| int [IndexOfKey](./indexofkey/)(TKey) const | به دنبال کلید خاصی می‌گردد. |
| int [IndexOfValue](./indexofvalue/)(TValue) const | به دنبال مقدار خاصی می‌گردد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل اپراتور 'is' در C#. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انبارگر را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا تمام عناصر یک دنباله یک شرط را ارضا می‌کنند. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | تعیین می‌کند آیا دنباله شامل هر عنصر یا نه. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا هر عنصر از دنباله وجود دارد یا شرطی را ارضا می‌کند. |
| T [LINQ_Average](../ienumerable/linq_average/)() | میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین یک دنباله از مقادیری که با فراخوانی تابع تبدیل بر هر عنصر دنباله ورودی به دست می‌آید را محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | عناصری را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | دو دنباله را به هم می‌چسباند. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | تعیین می‌کند آیا دنباله شامل مقدار مشخصی است یا نه. |
| int [LINQ_Count](../ienumerable/linq_count/)() | تعداد عناصر در دنباله را برمی‌گرداند (محاسبه‌شده با شمارش مستقیم). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصر در دنباله که شرط مشخص‌شده را ارضا می‌کنند را برمی‌گرداند. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | عنصر در ایندکس مشخص در دنباله را برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | عنصر در ایندکس مشخص در دنباله را برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)() | اولین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصری از دنباله که شرط مشخص‌شده را ارضا می‌کند را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | اولین عنصر دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصری از دنباله که شرط را ارضا می‌کند یا مقدار پیش‌فرض اگر چنین عنصری پیدا نشود را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | آخرین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | آخرین عنصر دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنباله عمومی اجرا می‌کند و حداکثر مقدار به‌دست آمده را برمی‌گرداند. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنباله عمومی اجرا می‌کند و حداقل مقدار به‌دست آمده را برمی‌گرداند. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را به ترتیب صعودی بر اساس مقادیر کلیدی که توسط keySelector انتخاب شده‌اند، مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را به ترتیب نزولی بر اساس مقادیر کلیدی که توسط keySelector انتخاب شده‌اند، مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | ترتیب عناصر یک دنباله را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر از دنباله را به شکل جدیدی تبدیل می‌کند که شامل ایندکس عنصر می‌شود. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | هر عنصر از دنباله را پیش‌بینی می‌کند و دنباله‌های حاصل را به یک دنباله ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | تعدادی عنصر متوالی مشخص از ابتدای دنباله عبور می‌دهد و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای دنباله برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | یک آرایه از دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | یک List<T> از دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | یک دنباله را بر اساس شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | یک شیء ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | عملگر انتساب جابجایی. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | عملگر انتساب جابجایی. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | دستیابی به دستگا برعکس که به آخرین عنصر مجموعه (اولین در جهت معکوس) اشاره می‌کند. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | دستیابی به دستگا برعکس که به آخرین عنصر مجموعه با قابلیت const (اولین در جهت معکوس) اشاره می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر حسب مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | کلید را از مخزن حذف می‌کند. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | عنصر را از مجموعه حذف می‌کند. |
| void [RemoveAt](./removeat/)(int) | مورد را در موقعیت مشخص حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد ارجاع‌های مشترک را به مقدار مشخص کاهش می‌دهد. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | دستیابی به دستگا برعکس برای یک عنصر غیرموجود پیش از آغاز مجموعه. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | دستیابی به دستگا برعکس برای یک عنصر غیرموجود پیش از آغاز مجموعه با قابلیت const. |
| void [set_Capacity](./set_capacity/)(int) | ظرفیت فعلی لیست را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [SortedList](./sortedlist/)() | یک لیست خالی می‌سازد. |
|  [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<TKey\>\>\&) | یک لیست خالی می‌سازد. |
|  [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | سازنده کپی. |
|  [SortedList](./sortedlist/)(const [map_t](./map_t/)\&) | سازنده کپی. |
|  [SortedList](./sortedlist/)(int) | یک لیست خالی می‌سازد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | به دنبال مقدار می‌گردد و اگر یافت شد آن را بازیابی می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری دستور lock() در C# را باز می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | پیاده‌سازی begin iterator ثابت برای مخزن فعلی را دریافت می‌کند. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | پیاده‌سازی begin iterator برای مخزن فعلی را دریافت می‌کند. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | پیاده‌سازی end iterator ثابت برای مخزن فعلی را دریافت می‌کند. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | پیاده‌سازی end iterator برای مخزن فعلی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../icollection/~icollection/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داخلی را آزاد می‌سازد. |

## تعریف‌های نوع

| تعریف نوع | توضیح |
| --- | --- |
| [KeyCollection](./keycollection/) | نوع مجموعه کلیدها. |
| [ValueCollection](./valuecollection/) | نوع مجموعه مقدارها. |
| [map_t](./map_t/) | نوع داده پایه. |
| [this_t](./this_t/) | این نوع. |
| [Ptr](./ptr/) | نوع اشاره‌گر. |
| [KVPair](./kvpair/) | نوع جفت کلید-مقدار. |
| [IEnumerablePtr](./ienumerableptr/) | نوع مجموعه‌ای از جفت‌های مشابه. |
| [IEnumeratorPtr](./ienumeratorptr/) | نوع **Enumerator**. |
| [iterator](./iterator/) | نوع iterator. |
| [const_iterator](./const_iterator/) | نوع const iterator. |
| [reverse_iterator](./reverse_iterator/) | نوع reverse iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | نوع const reverse iterator. |

## مراجع

* کلاس [SortedListHelper](../sortedlisthelper/)
* کلاس [BaseDictionary](../basedictionary/)
* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)