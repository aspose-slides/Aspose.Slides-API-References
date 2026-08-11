---
title: StringDictionary
second_title: مرجع API Aspose.Slides برای C++
description: "دیکشنری رشته به رشته. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را درون اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 53
url: /fa/system.collections.specialized/stringdictionary/
---
## کلاس StringDictionary

[String](../../system/string/) به دیکشنری رشته‌ای. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را درون اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class StringDictionary : public System::Collections::Generic::Dictionary<String, String>
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [Add](../../system.collections.generic/idictionary/add/)(const TKey\&, const TValue\&) | یک جفت کلید-مقدار را به مخزن اضافه می‌کند. |
| virtual void [Add](../../system.collections.generic/icollection/add/)(const T\&) | یک عنصر را به مجموعه اضافه می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | یک تکرارگر را برمی‌گرداند که به اولین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این تکرارگر نمی‌تواند برای تغییر شیء ارجاع‌داده‌شده استفاده شود زیرا [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | یک تکرارگر را برمی‌گرداند که به اولین عنصر (در صورت وجود) از نمونه‌ی با خاصیت const مجموعه اشاره می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | یک تکرارگر را برمی‌گرداند که به اولین عنصر با خاصیت const (در صورت وجود) مجموعه اشاره می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | یک تکرارگر را برمی‌گرداند که درست پس از آخرین عنصر با خاصیت const (در صورت وجود) مجموعه اشاره می‌کند. |
| virtual void [Clear](../../system.collections.generic/icollection/clear/)() | تمام عناصر را از مجموعه حذف می‌کند. |
| virtual **bool** [Contains](../../system.collections.generic/icollection/contains/)(const T\&) const | بررسی می‌کند که آیا عنصر در مجموعه موجود است یا خیر. |
| virtual **bool** [ContainsKey](../../system.collections.generic/idictionary/containskey/)(const TKey\&) const | بررسی می‌کند که آیا مخزن شامل کلید است یا خیر. |
| void [CopyTo](../../system.collections.generic/idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../../system.collections.generic/keyvaluepair/)\<TKey, TValue\>\>, int) override | محتویات دیکشنری را در عناصر موجود آرایه کپی می‌کند. |
|  [Dictionary](../../system.collections.generic/dictionary/dictionary/)() | یک دیکشنری خالی ایجاد می‌کند. |
|  [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [map_t](../../system.collections.generic/dictionary/map_t/)\&) | داده‌ها را از نقشه کپی می‌کند. |
|  [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int) | بارگذاری‌مجدد که مطابق با ایجاد دیکشنری پیش‌اختصاصی است؛ در واقع هیچ تخصیصی انجام نمی‌دهد. |
|  [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../../system.collections.generic/idictionary/)\<TKey, TValue\>\>\&) | سازنده کپی. |
|  [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../../system.collections.generic/idictionary/)\<TKey, TValue\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<TKey\>\>\&) | سازنده کپی. |
|  [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<TKey\>\>\&) | یک دیکشنری خالی ایجاد می‌کند. |
|  [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int, const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<TKey\>\>\&) | یک دیکشنری خالی ایجاد می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | یک تکرارگر را برمی‌گرداند که درست پس از آخرین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این تکرارگر نمی‌تواند برای تغییر شیء ارجاع‌داده‌شده استفاده شود زیرا [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | یک تکرارگر را برمی‌گرداند که درست پس از آخرین عنصر (در صورت وجود) از نمونه‌ی با خاصیت const مجموعه اشاره می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌عبور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌عبور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual int [get_Count](../../system.collections.generic/icollection/get_count/)() const | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
| **bool** [get_IsFixedSize](../../system.collections.generic/idictionary/get_isfixedsize/)() const | بررسی می‌کند که آیا اندازهٔ مجموعه ثابت است یا خیر. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | بررسی می‌کند که آیا مجموعه فقط-خواندنی است یا خیر. |
| **bool** [get_IsSynchronized](../../system.collections.generic/idictionary/get_issynchronized/)() const | بررسی می‌کند که آیا مخزن ایمن برای چندنخی است یا خیر. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../../system.collections.generic/icollection/)\<TKey\>\> [get_Keys](../../system.collections.generic/idictionary/get_keys/)() const | به مجموعهٔ کلیدها دسترسی می‌یابد. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | شیء‌ای را که مجموعه از طریق آن همگام‌سازی می‌شود، برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../../system.collections.generic/icollection/)\<TValue\>\> [get_Values](../../system.collections.generic/idictionary/get_values/)() const | به مجموعهٔ مقادیر دسترسی می‌یابد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را برمی‌گرداند. |
| [IEnumeratorPtr](../../system.collections.generic/dictionary/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/dictionary/getenumerator/)() override | یک شیء شمارشگر ایجاد می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌سازی اشیاء سفارشی را ممکن می‌سازد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey\&) const | اگر پیدا شود مقدار را برمی‌گرداند؛ در غیر این صورت **Value()** را برمی‌گرداند. |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | اگر پیدا شود مقدار را برمی‌گرداند؛ در غیر این صورت **defaultValue** را برمی‌گرداند. |
| virtual TValue [GetValueOrNull](../../system.collections.generic/idictionary/getvalueornull/)(const TKey\&) const | اگر پیدا شود مقدار را برمی‌گرداند؛ در غیر این صورت **null** را برمی‌گرداند، که فقط برای انواع ارجاعی معنا دارد. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | سازنده پیش‌فرض. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | سازندهٔ کپی. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | سازندهٔ جابجایی. |
| [String](../../system/string/) [idx_get](./idx_get/)(const [String](../../system/string/)\&) const override | مقدار مرتبط با کلید خاص را برمی‌گرداند. |
| virtual TValue [idx_get](../../system.collections.generic/idictionary/idx_get/)(const TKey\&) const | تابع گتر. |
| virtual void [idx_set](../../system.collections.generic/idictionary/idx_set/)(const TKey\&, TValue) | تابع ستر. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. مشابه عملگر C# `is`. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انباشت‌کننده را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا تمام عناصر یک دنباله شرط را برآورده می‌کنند یا خیر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | تعیین می‌کند که آیا یک دنباله شامل هر عنصرى است یا خیر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا هر عنصر از یک دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین یک دنباله از مقادیری را که با فراخوانی تابع تبدیل بر هر عنصر دنباله ورودی به‌دست می‌آید، محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | دو دنباله را به‌هم می‌پیوندد. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تعیین می‌کند که آیا یک دنباله شامل مقدار مشخصی است یا خیر. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | تعداد عناصر موجود در دنباله را برمی‌گرداند (محاسبه‌شده با شمارش مستقیم). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری را که شرط مشخص‌شده را برآورده می‌کنند، برمی‌گرداند. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | عنصر موجود در اندیس مشخص شده در یک دنباله را برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | عنصر موجود در اندیس مشخص شده در یک دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | اولین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصر دنباله‌ای که شرط مشخص‌شده را برآورده می‌کند، برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | اولین عنصر دنباله را یا مقدار پیش‌فرض اگر دنباله خالی باشد، برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصر دنباله‌ای که شرط را برآورده می‌کند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود، برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | آخرین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | آخرین عنصر دنباله را یا مقدار پیش‌فرض اگر دنباله خالی باشد، برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و بیشترین مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و کمترین مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به‌صورت صعودی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به‌صورت نزولی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ترتیب عناصر یک دنباله را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر از یک دنباله را با درنظر گرفتن اندیس عنصر به شکل جدیدی تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | هر عنصر یک دنباله را پروژه می‌کند و دنباله‌های حاصل را در یک دنباله ترکیب می‌سازد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر پیوسته را از ابتدای یک دنباله حذف می‌کند و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر پیوسته را از ابتدای یک دنباله برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | یک آرایه از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | یک دنباله را بر اساس پیش‌شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌کردن بیان C# `lock()` را انجام می‌دهد. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | عملگر انتساب جابجایی. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | عملگر انتساب جابجایی. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| virtual **bool** [Remove](../../system.collections.generic/idictionary/remove/)(const TKey\&) | کلید را از مخزن حذف می‌کند. |
| virtual **bool** [Remove](../../system.collections.generic/icollection/remove/)(const T\&) | عنصر را از مجموعه حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الیتمپلیت nام را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای shared). امکان تغییر اشاره‌گرها در مخازن به حالت weak را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را می‌دهد. |
| virtual **bool** [TryGetValue](../../system.collections.generic/idictionary/trygetvalue/)(const TKey\&, TValue\&) const | به دنبال مقدار می‌گردد و در صورت یافتن آن را برمی‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار C# `typeof([System.Object](../../system/object/))` را انجام می‌دهد. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازکردن قفل بیان C# `lock()` را انجام می‌دهد. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | پیاده‌سازی آغازگر تکرارگر const را برای مخزن جاری برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | پیاده‌سازی آغازگر تکرارگر را برای مخزن جاری برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | پیاده‌سازی پایان‌دهنده تکرارگر const را برای مخزن جاری برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | پیاده‌سازی پایان‌دهنده تکرارگر را برای مخزن جاری برمی‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | دست‌نایاب. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Dictionary](../../system.collections.generic/dictionary/)
* فضای‌نام [System::Collections::Specialized](../)
* کتابخانه [Aspose.Slides](../../)