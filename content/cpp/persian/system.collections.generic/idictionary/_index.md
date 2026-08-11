---
title: IDictionary
second_title: "مرجع API Aspose.Slides برای C++"
description: "رابط برای کانتینرهای مشابه دیکشنری. اشیای این کلاس باید تنها با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اعتبارسنجی می‌شود. همیشه این کلاس را در اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 274
url: /fa/system.collections.generic/idictionary/
---
## IDictionary کلاس

رابط برای کانتینرهای مشابه دیکشنری. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اعتبارسنجی می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلید. |
| TValue | نوع مقدار. |

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [Add](./add/)(const TKey\&, const TValue\&) | یک جفت کلید-مقدار را به کانتینر اضافه می‌کند. |
| virtual void [Add](../icollection/add/)(const T\&) | عنصری را به مجموعه اضافه می‌کند. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | یک iterator دریافت می‌کند که به اولین عنصر (در صورت وجود) مجموعه اشاره دارد. این iterator نمی‌تواند برای تغییر شیء ارجاع‌شده استفاده شود زیرا [GetEnumerator()](../ienumerable/getenumerator/) یک شیء کپی از T را برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | یک iterator دریافت می‌کند که به اولین عنصر (در صورت وجود) نمونه با خصوصیت const مجموعه اشاره دارد. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | یک iterator دریافت می‌کند که به اولین عنصر با خصوصیت const (در صورت وجود) مجموعه اشاره دارد. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | یک iterator دریافت می‌کند که درست پس از آخرین عنصر با خصوصیت const (در صورت وجود) مجموعه اشاره دارد. |
| virtual void [Clear](../icollection/clear/)() | تمام عناصر را از مجموعه حذف می‌کند. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | بررسی می‌کند که آیا عنصر در مجموعه حضور دارد یا نه. |
| virtual **bool** [ContainsKey](./containskey/)(const TKey\&) const | بررسی می‌کند که آیا کانتینر شامل کلید است یا نه. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | محتویات دیکشنری را به عناصر آرایه موجود کپی می‌کند. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | یک iterator دریافت می‌کند که درست پس از آخرین عنصر (در صورت وجود) مجموعه اشاره دارد. این iterator نمی‌تواند برای تغییر شیء ارجاع‌شده استفاده شود زیرا [GetEnumerator()](../ienumerable/getenumerator/) یک شیء کپی از T را برمی‌گرداند. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | یک iterator دریافت می‌کند که درست پس از آخرین عنصر (در صورت وجود) نمونه با خصوصیت const مجموعه اشاره دارد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنی‌گری C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر مطابق IEC 60559:1989 NaN با هیچ مقداری، حتی NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر مطابق IEC 60559:1989 NaN با هیچ مقداری، حتی NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| virtual int [get_Count](../icollection/get_count/)() const | تعداد عناصر موجود در مجموعه را دریافت می‌کند. |
| **bool** [get_IsFixedSize](./get_isfixedsize/)() const | بررسی می‌کند که آیا اندازهٔ مجموعه ثابت است یا نه. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | بررسی می‌کند که آیا مجموعه فقط-خواندنی است یا نه. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() const | بررسی می‌کند که آیا کانتینر ایمن در برابر رشته‌ها است یا نه. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](./get_keys/)() const | به مجموعهٔ کلیدها دسترسی می‌یابد. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | شیئی که از طریق آن مجموعه همگام‌سازی می‌شود را دریافت می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](./get_values/)() const | به مجموعهٔ مقادیر دسترسی می‌یابد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | شمارنده را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey\&) const | اگر مقدار یافت شد، آن را بازمی‌گرداند؛ در غیر این صورت **Value()** را بازمی‌گرداند. |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey\&, const TValue\&) const | اگر مقدار یافت شد، آن را بازمی‌گرداند؛ در غیر این صورت **defaultValue** را بازمی‌گرداند. |
| virtual TValue [GetValueOrNull](./getvalueornull/)(const TKey\&) const | اگر مقدار یافت شد، آن را بازمی‌گرداند؛ در غیر این صورت **null** را بازمی‌گرداند؛ فقط برای انواع مرجع معنا دارد. |
| [ICollection](../icollection/icollection/)() | سازندهٔ پیش‌فرض. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | سازندهٔ کپی. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | سازندهٔ جابجایی. |
| virtual TValue [idx_get](./idx_get/)(const TKey\&) const | تابع دریافت‌کننده. |
| virtual void [idx_set](./idx_set/)(const TKey\&, TValue) | تابع تنظیم‌کننده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انباشتگر را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا تمام عناصر یک دنباله یک شرط را برآورده می‌کنند. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | تعیین می‌کند آیا یک دنباله شامل هر عنصری است. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا هر عنصر از یک دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../ienumerable/linq_average/)() | میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین یک دنباله از مقادیر که با اعمال یک تابع تبدیل بر هر عنصر دنبالهٔ ورودی به‌دست می‌آیند را محاسبه می‌کند. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | دو دنباله را به هم می‌چسباند. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | تعیین می‌کند آیا یک دنباله شامل مقدار مشخصی است. |
| int [LINQ_Count](../ienumerable/linq_count/)() | تعداد عناصر دنباله را برمی‌گرداند (محاسبه شده به‌صورت شمارش مستقیم). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری از دنباله که شرط مشخص‌شده را برآورده می‌کنند را برمی‌گرداند. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | عنصر در اندیس مشخص‌شده در یک دنباله را برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | عنصر در اندیس مشخص‌شده در یک دنباله را برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)() | اولین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصر دنباله‌ای که شرط مشخص‌شده را برآورده می‌کند را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | اولین عنصر دنباله، یا مقدار پیش‌فرض اگر دنباله خالی باشد را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصر دنباله‌ای که شرطی را برآورده می‌کند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | آخرین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | آخرین عنصر دنباله، یا مقدار پیش‌فرض اگر دنباله خالی باشد را برمی‌گرداند. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنباله عمومی اعمال می‌کند و بیشینهٔ مقدار حاصل را بازمی‌گرداند. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنباله عمومی اعمال می‌کند و کمینهٔ مقدار حاصل را بازمی‌گرداند. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | عناصر دنباله را بر پایهٔ نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به ترتیب صعودی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به ترتیب نزولی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | ترتیب عناصر یک دنباله را برعکس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر یک دنباله را با در نظر گرفتن اندیس عنصر به شکل جدیدی تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | هر عنصر یک دنباله را پروژه می‌کند و دنباله‌های حاصل را به یک دنباله ترکیب می‌نماید. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای دنباله عبور داده و بقیه را بازمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای دنباله بازمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | یک آرایه از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | دنباله را بر مبنای پیش‌شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | عملگر انتساب جابجایی. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | عملگر انتساب جابجایی. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | خاص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | خاص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| virtual **bool** [Remove](./remove/)(const TKey\&) | کلید را از کانتینر حذف می‌کند. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | عنصر را از مجموعه حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| virtual **bool** [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | به دنبال مقدار می‌گردد و اگر یافت شد آن را بازیابی می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازماندهی عبارت C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌کردن عبارت C# lock() را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | پیاده‌سازی begin const iterator برای کانتینر جاری را دریافت می‌کند. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | پیاده‌سازی begin iterator برای کانتینر جاری را دریافت می‌کند. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | پیاده‌سازی end const iterator برای کانتینر جاری را دریافت می‌کند. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | پیاده‌سازی end iterator برای کانتینر جاری را دریافت می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [BaseType](./basetype/) | نوع رابط پایه. |
| [KeyValuePairType](./keyvaluepairtype/) | نوع جفت کلید-مقدار. |

## مراجع

* کلاس [ICollection](../icollection/)
* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)