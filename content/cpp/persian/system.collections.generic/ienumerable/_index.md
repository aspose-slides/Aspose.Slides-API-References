---
title: IEnumerable
second_title: مرجع API Aspose.Slides برای C++
description: رابط شیئی که شمارنده‌ای بر روی عناصر موجود فراهم می‌کند.
type: docs
weight: 287
url: /fa/system.collections.generic/ienumerable/
---
## IEnumerable کلاس

رابط شیئی که شمارنده‌ای بر روی عناصر موجود فراهم می‌کند.

```cpp
template<typename T>class IEnumerable : public virtual System::Object
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | Element type. |

## متدها

| متد | توضیح |
| --- | --- |
| [iterator](./iterator/) [begin](./begin/)() | دستگاه تکرارگر را که به اولین عنصر (در صورت وجود) مجموعه اشاره می‌کند، برمی‌گرداند. این تکرارگر نمی‌تواند برای تغییر شیء مرجع استفاده شود زیرا [GetEnumerator()](./getenumerator/) یک شیء نسخه‌برداری‌شده از T را برمی‌گرداند. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | دستگاه تکرارگر را که به اولین عنصر (در صورت وجود) نمونهٔ دارای صفت const از مجموعه اشاره می‌کند، برمی‌گرداند. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | دستگاه تکرارگر را که به اولین عنصر دارای صفت const (در صورت وجود) مجموعه اشاره می‌کند، برمی‌گرداند. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | دستگاه تکرارگر را که درست پس از آخرین عنصر دارای صفت const (در صورت وجود) مجموعه اشاره می‌کند، برمی‌گرداند. |
| [iterator](./iterator/) [end](./end/)() | دستگاه تکرارگر را که درست پس از آخرین عنصر (در صورت وجود) مجموعه اشاره می‌کند، برمی‌گرداند. این تکرارگر نمی‌تواند برای تغییر شیء مرجع استفاده شود زیرا [GetEnumerator()](./getenumerator/) یک شیء نسخه‌برداری‌شده از T را برمی‌گرداند. |
| [const_iterator](./const_iterator/) [end](./end/)() const | دستگاه تکرارگر را که درست پس از آخرین عنصر (در صورت وجود) نمونهٔ دارای صفت const از مجموعه اشاره می‌کند، برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی استفاده می‌شود. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() | شمارنده را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هشت‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونهٔ از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| T [LINQ_Aggregate](./linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع جمع‌کننده را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](./linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا تمام عناصر یک دنباله یک شرط را برآورده می‌کنند. |
| **bool** [LINQ_Any](./linq_any/)() | تعیین می‌کند که آیا دنباله شامل هر عنصری است. |
| **bool** [LINQ_Any](./linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا هر عنصر از دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](./linq_average/)() | میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](./linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین یک دنباله از مقادیر را که با فراخوانی یک تابع تبدیل بر هر عنصر دنباله ورودی به‌دست می‌آیند، محاسبه می‌کند. |
| ResultType [LINQ_Average](./linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Cast](./linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل (کست) می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Cast](./linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Concat](./linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\>) | دو دنباله را به‌هم می‌چسباند. |
| **bool** [LINQ_Contains](./linq_contains/)(T) | تعیین می‌کند که آیا دنباله شامل مقدار مشخصی است. |
| int [LINQ_Count](./linq_count/)() | تعداد عناصر دنباله را برمی‌گرداند (محاسبه‌شده با شمارش مستقیم). |
| int [LINQ_Count](./linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری از دنباله که شرط مشخص‌شده را برآورده می‌کنند، برمی‌گرداند. |
| T [LINQ_ElementAt](./linq_elementat/)(int) | عنصر در ایندکس مشخص‌شده‌ای از دنباله را برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](./linq_elementatordefault/)(int) | عنصر در ایندکس مشخص‌شده‌ای از دنباله را برمی‌گرداند. |
| T [LINQ_First](./linq_first/)() | اولین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_First](./linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصری از دنباله که شرط مشخص‌شده را برآورده می‌کند، برمی‌گرداند. |
| T [LINQ_FirstOrDefault](./linq_firstordefault/)() | اولین عنصر دنباله یا مقدار پیش‌فرض اگر دنباله خالی باشد، برمی‌گرداند. |
| T [LINQ_FirstOrDefault](./linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصری از دنباله که شرطی را برآورده می‌کند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشد، برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](./linq_last/)() | آخرین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](./linq_lastordefault/)() | آخرین عنصر دنباله یا مقدار پیش‌فرض اگر دنباله خالی باشد، برمی‌گرداند. |
| ResultType [LINQ_Max](./linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و بیشینه مقدار نتیجه را برمی‌گرداند. |
| ResultType [LINQ_Max](./linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](./linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و کمینه مقدار نتیجه را برمی‌گرداند. |
| ResultType [LINQ_Min](./linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_OfType](./linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_OfType](./linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](./linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب صعودی بر حسب مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](./linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](./linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب نزولی بر حسب مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](./linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Reverse](./linq_reverse/)() | ترتیب عناصر یک دنباله را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر دنباله را با در نظر گرفتن ایندکس عنصر به شکل جدیدی تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_SelectMany](./linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\>\>\&) | هر عنصر دنباله را پروژه می‌کند و دنباله‌های حاصل را در یک دنباله ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_SelectMany](./linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Skip](./linq_skip/)(**int32_t**) | تعداد مشخصی عنصر پی‌در-پی از ابتدای دنباله را رد می‌کند و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Take](./linq_take/)(**int32_t**) | تعداد مشخصی عنصر پی‌در-پی از ابتدای دنباله را برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](./linq_toarray/)() | یک آرایه از دنباله می‌سازد. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](./linq_tolist/)() | یک List<T> از دنباله می‌سازد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Where](./linq_where/)(std::function\<**bool**(T)>) | یک دنباله را بر اساس شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | عملگر قفل‌گذاری C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های مشتق را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های مشتق را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء‌ی نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده‌ای کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازندهٔ typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | عملگر بازکردن قفل C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const | پیاده‌سازی begin const iterator برای کانتینر جاری را برمی‌گرداند. |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() | پیاده‌سازی begin iterator برای کانتینر جاری را برمی‌گرداند. |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const | پیاده‌سازی end const iterator برای کانتینر جاری را برمی‌گرداند. |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() | پیاده‌سازی end iterator برای کانتینر جاری را برمی‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [IEnumeratorType](./ienumeratortype/) | نوع شمارنده. |
| [ValueType](./valuetype/) |  |
| [iterator](./iterator/) | نوع تکرارگر. |
| [const_iterator](./const_iterator/) | نوع تکرارگر ثابت. |
| [virtualized_iterator](./virtualized_iterator/) | نوع پایهٔ تکرارگر داخلی. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | نوع عنصر تکرارگر داخلی. |

## همچنین ببینید

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)