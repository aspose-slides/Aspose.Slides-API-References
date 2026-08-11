---
title: ConcurrentDictionary
second_title: "مرجع API Aspose.Slides برای C++"
description: "پیاده‌سازی دیکشنری ایمن در برابر نخ. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اثبات می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال آن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 1
url: /fa/system.collections.concurrent/concurrentdictionary/
---
## ConcurrentDictionary کلاس

Thread-safe dictionary implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class TKey,class TValue>class ConcurrentDictionary : public System::Collections::Generic::Dictionary<TKey, TValue>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلید. |
| TValue | نوع مقدار. |
## متدها

| متد | توضیح |
| --- | --- |
| void [Add](./add/)(const TKey&, const TValue&) override | مقدار را به دیکشنری اضافه می‌کند. |
| virtual void [Add](../../system.collections.generic/idictionary/add/)(const TKey&, const TValue&) | جفت کلید-مقدار را به محفظه اضافه می‌کند. |
| virtual void [Add](../../system.collections.generic/icollection/add/)(const T&) | عنصری به مجموعه اضافه می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | دستگاهی که به اولین عنصر (در صورت وجود) مجموعه اشاره می‌کند را برمی‌گرداند. این دستگا نمی‌تواند برای تغییر شیء ارجاع‌شده استفاده شود زیرا [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | دستگاهی که به اولین عنصر (در صورت وجود) نمونهٔ const-مزین شدهٔ مجموعه اشاره می‌کند را برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | دستگاهی که به اولین عنصر const-مزین (در صورت وجود) مجموعه اشاره می‌کند را برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | دستگاهی که دقیقاً بعد از آخرین عنصر const-مزین (در صورت وجود) مجموعه اشاره می‌کند را برمی‌گرداند. |
| void [Clear](./clear/)() override | تمام عناصر در محفظه را حذف می‌کند. |
| virtual **bool** [Contains](../../system.collections.generic/icollection/contains/)(const T&) const | بررسی می‌کند آیا عنصر در مجموعه حضور دارد. |
| virtual **bool** [ContainsKey](../../system.collections.generic/idictionary/containskey/)(const TKey&) const | بررسی می‌کند آیا محفظه شامل کلید است. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)<[System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)<TKey, TValue>>, int) override | عناصر محفظه را به عناصر موجود آرایه کپی می‌کند. |
| void [CopyTo](../../system.collections.generic/idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../../system.collections.generic/keyvaluepair/)<TKey, TValue>>, int) override | محتویات دیکشنری را به عناصر موجود آرایه کپی می‌کند. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)() | دیکشنری خالی ایجاد می‌کند. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [map_t](../../system.collections.generic/dictionary/map_t/)&) | داده‌ها را از نقشه کپی می‌کند. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int) | overloadی که با ایجاد دیکشنری پیش‌تخصیص‌شده مطابقت دارد؛ در واقع هیچ تخصیصی انجام نمی‌دهد. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../../system.collections.generic/idictionary/)<TKey, TValue>>&) | سازندهٔ کپی. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../../system.collections.generic/idictionary/)<TKey, TValue>>&, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>>&) | سازندهٔ کپی. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>>&) | دیکشنری خالی ایجاد می‌کند. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>>&) | دیکشنری خالی ایجاد می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | دستگاهی که دقیقاً بعد از آخرین عنصر (در صورت وجود) مجموعه اشاره می‌کند را برمی‌گرداند. این دستگا نمی‌تواند برای تغییر شیء ارجاع‌شده استفاده شود زیرا [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | دستگاهی که دقیقاً بعد از آخرین عنصر (در صورت وجود) نمونهٔ const-مزین شدهٔ مجموعه اشاره می‌کند را برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T1>::value&&\![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | فقط برای مقاصد داخلی. |
| virtual int [get_Count](../../system.collections.generic/icollection/get_count/)() const | تعداد عناصر در مجموعه را برمی‌گرداند. |
| **bool** [get_IsFixedSize](../../system.collections.generic/idictionary/get_isfixedsize/)() const | بررسی می‌کند آیا اندازهٔ مجموعه ثابت است. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | بررسی می‌کند آیا مجموعه فقط-خواندنی است. |
| **bool** [get_IsSynchronized](../../system.collections.generic/idictionary/get_issynchronized/)() const | بررسی می‌کند آیا محفظه ایمن در برابر چندین نخ است. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../../system.collections.generic/icollection/)<TKey>> [get_Keys](../../system.collections.generic/idictionary/get_keys/)() const | به مجموعهٔ کلیدها دسترسی می‌دهد. |
| [SharedPtr](../../system/sharedptr/)<typename [ThisType::KeyCollection](../../system.collections.generic/dictionary/keycollection/)> [get_KeysInternal](./get_keysinternal/)() const override | مجموعهٔ wrapper برای دسترسی به کلیدهای دیکشنری را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | شیئی که مجموعه از طریق آن همگام‌سازی می‌شود را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../../system.collections.generic/icollection/)<TValue>> [get_Values](../../system.collections.generic/idictionary/get_values/)() const | به مجموعهٔ مقدارها دسترسی می‌دهد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارشگر مرجع مرتبط با شیء را برمی‌گرداند. |
| [IEnumeratorPtr](../../system.collections.generic/dictionary/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/dictionary/getenumerator/)() override | شیء enumerator را ایجاد می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌کردن اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey&) const | مقدار را در صورت یافتن برمی‌گرداند؛ در غیر این صورت **Value()**. |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey&, const TValue&) const | مقدار را در صورت یافتن برمی‌گرداند؛ در غیر این صورت **defaultValue**. |
| virtual TValue [GetValueOrNull](../../system.collections.generic/idictionary/getvalueornull/)(const TKey&) const | مقدار را در صورت یافتن برمی‌گرداند؛ در غیر این صورت **null**، فقط برای انواع مرجع معنی دارد. |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | سازندهٔ پیش‌فرض. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)&) | سازندهٔ کپی. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)&&) | سازندهٔ جابه‌جایی. |
| virtual TValue [idx_get](../../system.collections.generic/idictionary/idx_get/)(const TKey&) const | تابع getter. |
| void [idx_set](./idx_set/)(const TKey&, TValue) override | عنصر را در موقعیت مشخصی تنظیم می‌کند. |
| virtual void [idx_set](../../system.collections.generic/idictionary/idx_set/)(const TKey&, TValue) | تابع setter. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# `is`. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | یک تابع accumulator را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function<**bool**(T)>) | تعیین می‌کند آیا تمام عناصر یک دنباله شرطی را ارضا می‌کنند. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | تعیین می‌کند آیا دنباله حاوی هر عنصری است. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function<**bool**(T)>) | تعیین می‌کند آیا هر عنصر از دنباله وجود دارد یا شرطی را ارضا می‌کند. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | متوسط مقادیر عددی یک دنباله را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | متوسط مقادیر یک دنباله را که توسط تابع تبدیل بر هر عنصر اعمال می‌شود محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>>) | دو دنباله را به هم الحاق می‌کند. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تعیین می‌کند آیا دنباله شامل مقدار مشخصی است. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | تعداد عناصر در دنباله را برمی‌گرداند (محاسبه‌شده با شمارش مستقیم). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | تعداد عناصری در دنباله که شرط مشخص‌شده را ارضا می‌کنند برمی‌گرداند. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | عنصر در اندیس مشخص‌شده در دنباله را برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | عنصر در اندیس مشخص‌شده در دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | اولین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | اولین عنصری از دنباله که شرط مشخص‌شده را ارضا می‌کند برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | اولین عنصر دنباله یا مقدار پیش‌فرض اگر دنباله خالی باشد را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | اولین عنصری از دنباله که شرط را ارضا می‌کند یا مقدار پیش‌فرض اگر چنین عنصری پیدا نشود را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | آخرین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | آخرین عنصر دنباله یا مقدار پیش‌فرض اگر دنباله خالی باشد را برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و حداکثر مقدار به‌دست‌آمده را برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و حداقل مقدار به‌دست‌آمده را برمی‌گرداند. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | عناصر یک دنباله را به ترتیب صعودی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | عناصر یک دنباله را به ترتیب نزولی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ترتیب عناصر یک دنباله را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | هر عنصر یک دنباله را با درنظر گرفتن ایندکس عنصر به فرم جدیدی تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>>>>&) | هر عنصر یک دنباله را پروجکت می‌کند و دنباله‌های حاصل را به یک دنباله ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>>>>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای دنباله حذف کرده و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای دنباله برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | آرایه‌ای از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[List](../../system.collections.generic/list/)<T>> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | List<T>‌ای از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function<**bool**(T)>) | دنباله‌ای را بر اساس پیش‌شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری عبارت C# `lock()` را انجام می‌دهد. مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء‌ای ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [ICollection](../../system.collections.generic/icollection/)& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)&&) | عملگر تخصیص جابه‌جایی. |
| [ICollection](../../system.collections.generic/icollection/)& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)&) | عملگر تخصیص جابه‌جایی. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | عملگر تخصیص. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| **bool** [Remove](./remove/)(const TKey&) override | عنصر را از محفظه حذف می‌کند. |
| virtual **bool** [Remove](../../system.collections.generic/idictionary/remove/)(const TKey&) | کلید را از محفظه حذف می‌کند. |
| virtual **bool** [Remove](../../system.collections.generic/icollection/remove/)(const T&) | عنصر را از مجموعه حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointer‌ها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع ضعیف را کاهش و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointer‌ها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| **bool** [TryAdd](./tryadd/)(const TKey&, const TValue&) | سعی می‌کند جفت کلید/مقدار را به دیکشنری اضافه کند. |
| virtual **bool** [TryGetValue](../../system.collections.generic/idictionary/trygetvalue/)(const TKey&, TValue&) const | به دنبال مقدار می‌گردد و در صورت یافتن آن را برمی‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | پیاده‌سازی سازوکار C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازکردن قفل عبارت C# `lock()` را انجام می‌دهد. مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | پیاده‌سازی iterator const `begin` برای محفظهٔ فعلی را برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | پیاده‌سازی iterator `begin` برای محفظهٔ فعلی را برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | پیاده‌سازی iterator const `end` برای محفظهٔ فعلی را برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | پیاده‌سازی iterator `end` برای محفظهٔ فعلی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointer‌ها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointer‌ها یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | مخرب (Destructor). |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## تعاریف نوع

| تعریف | توضیح |
| --- | --- |
| [ThisType](./thistype/) | این نوع. |
| [BaseType](./basetype/) | نوع پیاده‌سازی. |
## ملاحظات



```cpp
#include <system/collections/concurrent/concurrent_dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  const int itemsCount = 32;

  // یک نمونه از کلاس ConcurrentDictionary ایجاد کنید.
  auto concurrentDictionary = MakeObject<ConcurrentDictionary<int, int>>();

  // دیکشنری همزمان را پر کنید.
  for (auto i = 0; i < itemsCount; ++i)
  {
    concurrentDictionary->Add(i, i * i);
  }

  Console::WriteLine(concurrentDictionary->idx_get(3));

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
9
*/
```

## مراجع

* کلاس [Dictionary](../../system.collections.generic/dictionary/)
* فضای نام [System::Collections::Concurrent](../)
* کتابخانه [Aspose.Slides](../../)