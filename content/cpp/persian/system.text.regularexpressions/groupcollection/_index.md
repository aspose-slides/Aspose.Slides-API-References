---
title: GroupCollection
second_title: مرجع API Aspose.Slides برای C++
description: "فهرست گروه‌های ضبط‌شده در یک تطبیق واحد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا باعث خطاهای زمان اجرا و/یا شکست‌های assert می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به عنوان آرگومان به توابع استفاده کنید."
type: docs
weight: 40
url: /fa/system.text.regularexpressions/groupcollection/
---
## کلاس GroupCollection

فهرست گروه‌های ضبط‌شده در یک تطبیق واحد. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به عنوان آرگومان به توابع استفاده کنید.

```cpp
class GroupCollection : public System::Collections::Generic::List<GroupPtr>
```

## متدها

| Method | Description |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | خاص C++. |
| void [Add](./add/)(const [GroupPtr](../groupptr/)\&) override | اضافه کردن عنصر به مجموعه را غیرفعال می‌کند. |
| void [Add](../../system.collections.generic/list/add/)(const T \&) override | عنصر را به انتهای لیست اضافه می‌کند. |
| void [AddGroup](./addgroup/)(const [GroupPtr](../groupptr/)\&) | گروه را به مجموعه اضافه می‌کند. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | عناصر را به لیست اضافه می‌کند؛ هنگام ترجمه مقداردهی اولیه استفاده می‌شود. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | تمام عناصر را از مجموعه (یا خود مجموعه) به انتهای لیست جاری اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | مرجع فقط-خواندنی به این مجموعه را برمی‌گرداند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | تکرارگر به اولین عنصر مجموعه را برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | تکرارگر به اولین عنصر مجموعه‌ای که const-qualified است را برمی‌گرداند. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | در یک لیست مرتب به دنبال مورد می‌گردد. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | در یک لیست مرتب به دنبال مورد می‌گردد. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | در یک لیست مرتب به دنبال مورد می‌گردد. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | تکرارگر به اولین عنصر const-qualified مجموعه را برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | تکرارگر برای عنصری const-qualified که وجود ندارد و پشت انتهای مجموعه قرار دارد را برمی‌گرداند. |
| void [Clear](./clear/)() override | حذف عناصر از مجموعه را غیرفعال می‌کند. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | بررسی می‌کند که آیا مورد در لیست حضور دارد یا نه. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | یک لیست از عناصر تبدیل‌شده به نوع متفاوت ایجاد می‌کند. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | عناصر لیست را در عناصر آرایه موجود کپی می‌کند. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | تمام عناصر را در عناصر آرایه موجود کپی می‌کند. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | عناصر را از ایندکس مشخص‌شده شروع کرده و در عناصر آرایه موجود کپی می‌کند. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | یک تکرارگر معکوس به آخرین عنصر const-qualified مجموعه (اولین در جهت معکوس) برمی‌گرداند. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | تکرارگر معکوس برای عنصری const-qualified که وجود ندارند و قبل از شروع مجموعه قرار دارد را برمی‌گرداند. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | تابع دسترسی به ساختار داده‌ی زیرین. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | تابع دسترسی به ساختار داده‌ی زیرین. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | تکرارگر برای عنصری که وجود ندارد و پشت انتهای مجموعه قرار دارد را برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | تکرارگر برای عنصری که وجود ندارد و پشت انتهای مجموعه const-qualified قرار دارد را برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN مساوی در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN مساوی در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | بررسی می‌کند آیا عنصری که با پیش‌شرط خاصی مطابقت دارد در لیست وجود دارد یا نه. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که با پیش‌شرط خاصی مطابقت دارد. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عناصری می‌گردد که با پیش‌شرط خاصی مطابقت دارند. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که با پیش‌شرط خاصی مطابقت دارد. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که با پیش‌شرط خاصی مطابقت دارد. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که با پیش‌شرط خاصی مطابقت دارد. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال آخرین عنصری می‌گردد که با پیش‌شرط خاصی مطابقت دارد. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | عملی را بر تمام عناصر لیست اعمال می‌کند. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | ظرفیت فعلی لیست را برمی‌گرداند. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | تعداد عناصر در لیست جاری را برمی‌گرداند. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | بررسی می‌کند آیا مجموعه اندازه ثابت دارد یا نه. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | بررسی می‌کند آیا مجموعه فقط-خواندنی است یا نه. |
| [GroupPtr](../groupptr/) [get_Item](./get_item/)(int) const | [Group](../group/) دسترس‌ساز. |
| [GroupPtr](../groupptr/) [get_Item](./get_item/)(const [String](../../system/string/)\&) const | [Group](../group/) دسترس‌ساز. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | شیئی را برمی‌گرداند که مجموعه از طریق آن همگام‌سازی می‌شود. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | شمارنده‌ای برای تکرار عناصر لیست برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | بخش‌ایی از لیست را ایجاد می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GroupCollection](./groupcollection/)(const [WeakPtr](../../system/weakptr/)\<[Match](../match/)\>\&) | سازنده. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | سازنده پیش‌فرض. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | سازنده کپی. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | سازنده جابجایی. |
| virtual [GroupPtr](../groupptr/) [idx_get](./idx_get/)([String](../../system/string/)) const | [Group](../group/) دسترس‌ساز. |
| [GroupPtr](../groupptr/) [idx_get](./idx_get/)(int) const override | [Group](../group/) دسترس‌ساز. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | عنصر را در موقعیت خاص تنظیم می‌کند. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | اولین ایندکس مورد خاص را برمی‌گرداند. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | به دنبال مورد خاصی در لیست می‌گردد. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | مورد را در موقعیت مشخصی درج می‌کند. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | بازه‌ای از داده‌ها را در موقعیت خاص درج می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| **bool** [IsReadOnly](./isreadonly/)() const | مجموعه را به عنوان فقط-خواندنی علامت‌گذاری می‌کند. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | به‌دنبال شیء مشخص شده می‌گردد و ایندکس صفر-مبنای آخرین وقوع آن را در کل لیست برمی‌گرداند. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | به‌دنبال شیء مشخص شده می‌گردد و ایندکس صفر-مبنای آخرین وقوع آن را در بازه‌ای از عناصری که [List](../../system.collections.generic/list/) را از اولین عنصر تا ایندکس مشخص‌شده شامل می‌شود، برمی‌گرداند. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | به‌دنبال شیء مشخص شده می‌گردد و ایندکس صفر-مبنای آخرین وقوع آن را در بازه‌ای از عناصری که [List](../../system.collections.generic/list/) را شامل تعداد مشخصی عنصر می‌شود و در ایندکس مشخص‌شده پایان می‌یابد، برمی‌گرداند. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | تابع انباشت‌گر را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا تمام عناصر یک دنباله شرط را برآورده می‌کنند. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | تعیین می‌کند آیا دنباله شامل هر عنصرى است. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا هر عنصرى از دنباله وجود دارد یا شرط را برآورده می‌کند. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | میانگین یک دنباله از مقادیر که با فراخوانی تابع تبدیل بر هر عنصر از دنباله ورودی به‌دست می‌آید را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | عناصری را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | دو دنباله را به هم می‌چسباند. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تعیین می‌کند آیا دنباله شامل مقدار مشخصی است. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | تعداد عناصر در دنباله را برمی‌گرداند (محاسبه شده از طریق شمارش مستقیم). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری در دنباله که شرط مشخص‌شده را برآورده می‌کنند را برمی‌گرداند. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | عنصری را که در ایندکس مشخصی در دنباله قرار دارد برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | عنصری را که در ایندکس مشخصی در دنباله قرار دارد برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | اولین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصر دنباله که شرط مشخص‌شده را برآورده می‌کند را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | اولین عنصر دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصر دنباله که شرطی را برآورده می‌کند را برمی‌گرداند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | آخرین عنصر دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | آخرین عنصر دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنباله عمومی اجرا می‌کند و بیشینه مقدار حاصل را برمی‌گرداند. |
| [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنباله عمومی اجرا می‌کند و کمینه مقدار حاصل را برمی‌گرداند. |
| [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب صعودی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب نزولی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ترتیب عناصر در یک دنباله را معکوس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر یک دنباله را به فرم جدیدی تبدیل می‌کند به‌طوری که ایندکس عنصر را در بر گیرد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | هر عنصر یک دنباله را پروجکت می‌کند و دنباله‌های حاصل را به یک دنباله ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای یک دنباله رد می‌کند و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر متوالی از ابتدای یک دنباله را برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | یک آرایه از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | یک دنباله را بر اساس پیش‌شرط مشخص‌شده فیلتر می‌کند. |
|  [List](../../system.collections.generic/list/list/)() | یک لیست خالی ایجاد می‌کند. |
|  [List](../../system.collections.generic/list/list/)(int) | لیستی با ظرفیت پیش‌تعریف‌شده ایجاد می‌کند. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | سازنده کپی. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری دستورات C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | یک شیء ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی زیرکلاس‌ها را فراهم می‌کند. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | عملگر انتساب جابجایی. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | عملگر انتساب جابجایی. |
| [GroupPtr](../groupptr/) [operator[]](./operator[]/)(const [String](../../system/string/)\&) const | [Group](../group/) دسترس‌ساز. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | تابع دسترس‌ساز. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | تابع دسترس‌ساز. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | یک تکرارگر معکوس به آخرین عنصر مجموعه (اولین در جهت معکوس) برمی‌گرداند. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | یک تکرارگر معکوس به آخرین عنصر مجموعه const-qualified (اولین در جهت معکوس) برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌وار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| **bool** [Remove](./remove/)(const [GroupPtr](../groupptr/)\&) override | حذف عنصر از مجموعه را غیرفعال می‌کند. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | اولین نمونه از مورد خاص را از لیست حذف می‌کند. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | تمام عناصری که پیش‌شرط خاصی را برآورده می‌شوند را حذف می‌کند. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | موردی را در موقعیت مشخص حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | قسمتی از لیست را حذف می‌کند. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | یک تکرارگر معکوس برای عنصر غیرموجود قبل از شروع مجموعه برمی‌گرداند. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | یک تکرارگر معکوس برای عنصر غیرموجود قبل از شروع مجموعه const-qualified برمی‌گرداند. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | ترتیب عناصر کل لیست را معکوس می‌کند. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | ترتیب عناصر بخش مشخصی از لیست را معکوس می‌کند. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | ظرفیت لیست را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان n‌ام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تبدیل اشاره‌گرها در سازنده‌ها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | عناصر لیست را مرتب می‌کند. |
| void [Sort](../../system.collections.generic/list/sort/)() | عناصر لیست را با مقایسه‌گر پیش‌فرض مرتب می‌کند. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | عناصر بخش مشخصی از لیست را مرتب می‌کند. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | عناصر لیست را مرتب می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | لیست را به آرایه تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | ظرفیت لیست را به اندازهٔ واقعی آن تنظیم می‌کند. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | تعیین می‌کند آیا تمام عناصر مجموعه شرایط تعریف‌شده توسط پیش‌شرط مشخص‌شده را برآورده می‌کنند یا نه. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری دستورات C# lock() را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | پیاده‌سازی begin const iterator برای سازندهٔ فعلی را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | پیاده‌سازی begin iterator برای سازندهٔ فعلی را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | پیاده‌سازی end const iterator برای سازندهٔ فعلی را برمی‌گرداند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | پیاده‌سازی end iterator برای سازندهٔ فعلی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Base](./base/) | کلاس پایه. |

## مراجع

* کلاس [List](../../system.collections.generic/list/)
* فضای‌نام [System::Text::RegularExpressions](../)
* کتابخانه [Aspose.Slides](../../)