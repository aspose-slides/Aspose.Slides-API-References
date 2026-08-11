---
title: TabCollection
second_title: Aspose.Slides برای مرجع API C++
description: یک مجموعه از تب‌ها را نشان می‌دهد.
type: docs
weight: 5383
url: /fa/aspose.slides/tabcollection/
---
## TabCollection کلاس

Represents a collection of tabs.

```cpp
class TabCollection : public Aspose::Slides::ITabCollection,
                      public Aspose::Slides::IDOMObject
```

## متدها

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [Add](./add/)(**double**, [TabAlignment](../tabalignment/)) override | یک [Tab](../tab/) را به مجموعه اضافه می‌کند. |
| **int32_t** [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\>) override | یک [Tab](../tab/) را به مجموعه اضافه می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | دریافت‌کننده‌ای که به اولین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این دریافت‌کننده نمی‌تواند برای تغییر شی referenced استفاده شود چون [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شی نسخه‌برداری‌شده از T را باز می‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | دریافت‌کننده‌ای که به اولین عنصر (در صورت وجود) نمونه‌ی ثابت (const) مجموعه اشاره می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | دریافت‌کننده‌ای که به اولین عنصر const-Qualified (در صورت وجود) مجموعه اشاره می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | دریافت‌کننده‌ای که بلافعل آخرین عنصر const-Qualified (در صورت وجود) مجموعه اشاره می‌کند. |
| void [Clear](./clear/)() override | تمام عناصر مجموعه را حذف می‌کند. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\>\>, **int32_t**) override | تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | دریافت‌کننده‌ای که بلافعل آخرین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این دریافت‌کننده نمی‌تواند برای تغییر شی referenced استفاده شود چون [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شی نسخه‌برداری‌شده از T را باز می‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | دریافت‌کننده‌ای که بلافعل آخرین عنصر (در صورت وجود) نمونه‌ی ثابت (const) مجموعه اشاره می‌کند. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مشخص می‌کند آیا دو نمونه‌ی TabsEx برابر هستند یا خیر. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را بر اساس معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **int32_t** [get_Count](./get_count/)() override | تعداد عناصری که واقعاً در مجموعه وجود دارند را باز می‌گرداند. فقط-خواندنی **int32_t**. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن در برابر نخ) است. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | ریشهٔ همگام‌سازی را باز می‌گرداند. فقط-خواندنی [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شی را باز می‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\>\>\> [GetEnumerator](./getenumerator/)() override | یک enumerator که از مجموعه عبور می‌کند را باز می‌گرداند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | کد هش این شی را باز می‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را باز می‌گرداند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [idx_get](./idx_get/)(**int32_t**) override | عنصر در ایندکس مشخص‌شده را باز می‌گرداند. فقط-خواندنی [Tab](../tab/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی یک نمونه از نوعی است که توسط targetType توصیف شده. مشابه عملگر C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انباشتگر را بر روی یک توالی اعمال می‌کند. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | مشخص می‌کند آیا تمام عناصر یک توالی شرطی را برآورده می‌کنند. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | مشخص می‌کند آیا توالی شامل هر عنصری است یا خیر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | مشخص می‌کند آیا حداقل یک عنصر توالی وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | میانگین مقادیر عددی یک توالی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین مقادیر یک توالی را که با فراخوانی یک تابع تبدیل بر روی هر عنصر به‌دست می‌آید، محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | دو توالی را به‌هم می‌پیوندد. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تعیین می‌کند آیا توالی شامل مقدار مشخص‌شده‌ای است. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | تعداد عناصر توالی را برمی‌گرداند (از طریق شمارش مستقیم محاسبه می‌شود). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری از توالی که شرط مشخص‌شده را برآورده می‌کنند را برمی‌گرداند. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | عنصر در ایندکس مشخص‌شده در توالی را برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | عنصر در ایندکس مشخص‌شده در توالی را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | اولین عنصر توالی را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصر توالی که شرط مشخص‌شده را برآورده می‌کند را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | اولین عنصر توالی، یا مقدار پیش‌فرض اگر توالی خالی باشد، را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصر توالی که شرطی را برآورده می‌کند یا مقدار پیش‌فرض اگر عنصری یافت نشود را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک توالی را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک توالی را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | آخرین عنصر توالی را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | آخرین عنصر توالی، یا مقدار پیش‌فرض اگر توالی خالی باشد، را برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک توالی عمومی اعمال می‌کند و بیشینهٔ مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک توالی عمومی اعمال می‌کند و کمینهٔ مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | عناصر توالی را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر توالی را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به ترتیب صعودی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر توالی را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به ترتیب نزولی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ترتیب عناصر توالی را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک توالی را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر توالی را با درنظر گرفتن ایندکس عنصر به شکل جدیدی تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | هر عنصر توالی را به‌صورت نتایج پروژه می‌کند و توالی‌های حاصل را در یک توالی ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای توالی عبور می‌دهد و بقیه را باز می‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای توالی باز می‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | آرایه‌ای از یک توالی ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | یک List<T> از یک توالی ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | توالی را بر اساس پیش‌شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل کردن عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کپی‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | پیاده‌سازی خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | پیاده‌سازی خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| void [RemoveAt](./removeat/)(**int32_t**) override | عنصر در ایندکس مشخص‌شدهٔ مجموعه را حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را با مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را باز می‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | پیاده‌سازی begin const iterator برای محفظهٔ فعلی را باز می‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | پیاده‌سازی begin iterator برای محفظهٔ فعلی را باز می‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | پیاده‌سازی end const iterator برای محفظهٔ فعلی را باز می‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | پیاده‌سازی end iterator برای محفظهٔ فعلی را باز می‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [ITabCollection](../itabcollection/)
* کلاس [IDOMObject](../idomobject/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)