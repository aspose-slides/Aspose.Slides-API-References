---
title: ILineFormatCollection
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از سبک‌های خط را نشان می‌دهد.
type: docs
weight: 326
url: /fa/aspose.slides.theme/ilineformatcollection/
---
## ILineFormatCollection کلاس

نمایانگر مجموعهٔ سبک‌های خطی است.

```cpp
class ILineFormatCollection : public Aspose::Slides::IGenericCollection<System::SharedPtr<Aspose::Slides::ILineFormat>>
```

## متدها

| Method | Description |
| --- | --- |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | دریافت iterator که به اولین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این iterator نمی‌تواند برای تغییر شیء مرجع استفاده شود زیرا [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | دریافت iterator که به اولین عنصر (در صورت وجود) نمونهٔ با میان‌وضعیت const مجموعه اشاره می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | دریافت iterator که به اولین عنصر const-qualified (در صورت وجود) مجموعه اشاره می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | دریافت iterator که درست پس از آخرین عنصر const-qualified (در صورت وجود) مجموعه اشاره می‌کند. |
| virtual void [CopyTo](../../aspose.slides/igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | تمام عناصر مجموعه را در آرایهٔ مشخص‌شده کپی می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | دریافت iterator که درست پس از آخرین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این iterator نمی‌تواند برای تغییر شیء مرجع استفاده شود زیرا [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | دریافت iterator که درست پس از آخرین عنصر (در صورت وجود) نمونهٔ const-qualified مجموعه اشاره می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه مطابق IEC 60559:1989 NaN با هیچ‌مقداری، از جمله NaN برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور دو برابر به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه مطابق IEC 60559:1989 NaN با هیچ‌مقداری، از جمله NaN برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **int32_t** [get_Count](../../aspose.slides/igenericcollection/get_count/)() | تعداد رفتارها در یک مجموعه را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual **bool** [get_IsSynchronized](../../aspose.slides/igenericcollection/get_issynchronized/)() | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (ایمن برای چندنخی) است. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](../../aspose.slides/igenericcollection/get_syncroot/)() | ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../../system.collections.generic/ienumerable/getenumerator/)() | enumerator را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [idx_get](./idx_get/)(**int32_t**) | عنصری را که در اندیس مشخص قرار دارد دریافت می‌کند. فقط-خواندنی [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انباشتگر را روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا تمام عناصر یک دنباله یک شرط را ارضا می‌کنند. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | تعیین می‌کند که آیا یک دنباله شامل هر عنصرى است. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا حداقل یک عنصر از دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | میانگین یک دنبالهٔ مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین دنباله‌ای از مقادیر را که با فراخوانی یک تابع تبدیل بر هر عنصر دنبالهٔ ورودی به دست آمده‌اند، محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | دو دنباله را به هم می‌پیوندد. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تعیین می‌کند که آیا یک دنباله شامل مقدار مشخصی است. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | تعداد عناصر دنباله را برمی‌گرداند (محاسبه‌شده از طریق شمارش مستقیم). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری از دنباله را که شرط مشخص‌شده را ارضا می‌کنند برمی‌گرداند. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | عنصر در شاخص مشخص در یک دنباله را برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | عنصر در شاخص مشخص در یک دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | اولین عنصر یک دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصری از دنباله را که شرط مشخص‌شده را ارضا می‌کند برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | اولین عنصر یک دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصری از دنباله که شرطی را ارضا می‌کند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود، برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | آخرین عنصر یک دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | آخرین عنصر یک دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی فراخوانی می‌کند و بیشترین مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی فراخوانی می‌کند و کمترین مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به ترتیب صعودی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به ترتیب نزولی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ترتیب عناصر در یک دنباله را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر از دنباله را به شکل جدیدی تبدیل می‌کند که شامل اندیس عنصر می‌شود. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | هر عنصر از یک دنباله را پروژه می‌کند و دنباله‌های حاصل را در یک دنباله ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تعدادی مشخص از عناصر متوالی را از ابتدای یک دنباله رد می‌کند و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای یک دنباله برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | یک آرایه از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | یک دنباله را بر اساس پیش‌شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کپی‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها را به‌صورت کپی فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها را به‌صورت کپی فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به میزان مشخصی کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به weak pointer تنظیم می‌کند (به جای shared). اجازه می‌دهد تا اشاره‌گرها در کانتینرها به حالت weak تغییر کنند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیم فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با عبارت C# lock() را آزاد می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | اجرا (implementation) begin iterator ثابت برای کانتینر فعلی را دریافت می‌کند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | اجرا (implementation) begin iterator برای کانتینر فعلی را دریافت می‌کند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | اجرا (implementation) end iterator ثابت برای کانتینر فعلی را دریافت می‌کند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | اجرا (implementation) end iterator برای کانتینر فعلی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجع

* کلاس [IGenericCollection](../../aspose.slides/igenericcollection/)
* فضای‌نام [Aspose::Slides::Theme](../)
* کتابخانه [Aspose.Slides](../../)