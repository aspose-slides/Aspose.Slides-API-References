---
title: X509ExtensionCollection
second_title: مرجع API Aspose.Slides برای C++
description: "مجموعه‌ای از اشیای افزونه. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از operator new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات استنتاج می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور آن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 157
url: /fa/system.security.cryptography.x509certificates/x509extensioncollection/
---
## X509ExtensionCollection کلاس


مجموعه‌ای از اشیاء افزونه. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعای صحت می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال آن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class X509ExtensionCollection : public System::Collections::Generic::List<SharedPtr<X509Extension>>
```

## متدها

| متد | توضیح |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | خاص C++. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | عنصری را به انتهای لیست اضافه می‌کند. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | عناصر را به لیست اضافه می‌کند؛ هنگام ترجمهٔ مقداردهی اولیه استفاده می‌شود. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | تمام عناصر را از مجموعه (یا خود مجموعه) به انتهای لیست فعلی اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | یک مرجع فقط-خواندنی به این مجموعه دریافت می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | یک تکرارگر به اولین عنصر مجموعه دریافت می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | یک تکرارگر به اولین عنصر مجموعهٔ ثابت دریافت می‌کند. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | در یک لیست مرتب به دنبال آیتم می‌گردد. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | در یک لیست مرتب به دنبال آیتم می‌گردد. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | در یک لیست مرتب به دنبال آیتم می‌گردد. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | یک تکرارگر به اولین عنصر ثابتِ مجموعه دریافت می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | یک تکرارگر برای عنصر ثابت غیرموجود پشت انتهای مجموعه دریافت می‌کند. |
| void [Clear](../../system.collections.generic/list/clear/)() override | تمام عناصر را حذف می‌کند. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | بررسی می‌کند که آیا آیتم در لیست موجود است یا خیر. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | لیستی از عناصر تبدیل شده به نوع دیگری ایجاد می‌کند. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | عناصر لیست را در عناصر موجود آرایه کپی می‌کند. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | تمام عناصر را در عناصر موجود آرایه کپی می‌کند. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | عناصر را از ایندکس مشخص‌شده برای کپی به عناصر موجود آرایه کپی می‌کند. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | یک تکرارگر معکوس به آخرین عنصر ثابتِ مجموعه دریافت می‌کند (اولین در معکوس). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | یک تکرارگر معکوس برای عنصر ثابت غیرموجود قبل از شروع مجموعه دریافت می‌کند. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | تابع دسترسی به ساختار دادهٔ پایه. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | تابع دسترسی به ساختار دادهٔ پایه. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | یک تکرارگر برای عنصر غیرموجود پشت انتهای مجموعه دریافت می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | یک تکرارگر برای عنصر غیرموجود پشت انتهای مجموعهٔ ثابت دریافت می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | بررسی می‌کند که آیا عنصری مطابق پیش‌شرط خاص در لیست وجود دارد یا خیر. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که با پیش‌شرط خاصی مطابقت داشته باشد. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عناصری می‌گردد که با پیش‌شرط خاصی مطابقت داشته باشند. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که با پیش‌شرط خاصی مطابقت داشته باشد. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که با پیش‌شرط خاصی مطابقت داشته باشد. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | به دنبال عنصری می‌گردد که با پیش‌شرط خاصی مطابقت داشته باشد. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | به دنبال آخرین عنصری می‌گردد که با پیش‌شرط خاصی مطابقت داشته باشد. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | عملی را بر تمام عناصر لیست اعمال می‌کند. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | ظرفیت فعلی لیست را دریافت می‌کند. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | تعداد عناصر در لیست فعلی را دریافت می‌کند. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | بررسی می‌کند که آیا مجموعه اندازهٔ ثابت دارد یا خیر. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | بررسی می‌کند که آیا مجموعه فقط-خواندنی است یا خیر. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | شیئی که مجموعه از طریق آن همگام‌سازی می‌شود را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | یک شمارنده برای پیمایش عناصر لیست دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌سازی اشیاء سفارشی را امکان‌پذیر می‌سازد. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | یک برش از لیست ایجاد می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | سازندهٔ پیش‌فرض. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | سازندهٔ کپی. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | سازندهٔ جابجایی. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\> [idx_get](./idx_get/)(const [String](../../system/string/)\&) const | دسترس‌پذیر. پیاده‌سازی نشده. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | عنصری در موقعیت خاص دریافت می‌کند. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | عنصری را در موقعیت خاص تنظیم می‌کند. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | اولین اندیس آیتم خاص را دریافت می‌کند. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | به دنبال آیتم خاصی در لیست می‌گردد. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | آیتم را در موقعیت مشخص وارد می‌کند. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | بازهٔ داده‌ای را در موقعیت مشخص وارد می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | به دنبال شیء مشخص می‌گردد و اندیس صفر-پایهٔ آخرین رخداد آن در کل لیست را بازمی‌گرداند. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | به دنبال شیء مشخص می‌گردد و اندیس صفر-پایهٔ آخرین رخداد آن را در بازهٔ عناصری در [List](../../system.collections.generic/list/) که از اولین عنصر تا ایندکس مشخص گسترش دارد، بازمی‌گرداند. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | به دنبال شیء مشخص می‌گردد و اندیس صفر-پایهٔ آخرین رخداد آن را در بازهٔ عناصری در [List](../../system.collections.generic/list/) که شامل تعداد مشخصی عنصر است و در ایندکس مشخصی خاتمه می‌یابد، بازمی‌گرداند. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انباشتگر را بر یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا تمام عناصر یک دنباله شرطی را برآورده می‌کنند یا خیر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | تعیین می‌کند که آیا دنباله حاوی هر عنصرى است یا خیر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا هر عنصرى از دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | متوسط یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | متوسط دنباله‌ای از مقادیر را که با فراخوانی یک تابع تبدیل بر هر عنصر دنبالهٔ ورودی به دست می‌آید، محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | دو دنباله را به یکدیگر وصل می‌کند. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تعیین می‌کند که آیا دنباله شامل مقدار مشخصی است یا خیر. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | تعداد عناصر دنباله را بازمی‌گرداند (محاسبه شده از طریق شمارش مستقیم). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصری از دنباله که شرط مشخص‌شده را برآورده می‌کنند، بازمی‌گرداند. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | عنصری را در ایندکس مشخص‌شده در یک دنباله بازمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | عنصری را در ایندکس مشخص‌شده در یک دنباله بازمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | عنصر اول یک دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | عنصر اول یک دنباله که شرط مشخص شده را برآورده می‌کند، برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | عنصر اول یک دنباله را، یا مقدار پیش‌فرضی اگر دنباله خالی باشد، برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | عنصر اول دنباله‌ای که شرطی را برآورده می‌کند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود، برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | عنصر آخر یک دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | عنصر آخر یک دنباله را، یا مقدار پیش‌فرض اگر دنباله خالی باشد، برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر روی هر عنصر از یک دنباله عمومی فراخوانی می‌کند و حداکثر مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر روی هر عنصر از یک دنباله عمومی فراخوانی می‌کند و حداقل مقدار حاصل را برمی‌گرداند. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به صورت صعودی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به صورت نزولی مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ترتیب عناصر یک دنباله را برعکس می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر از یک دنباله را با در نظر گرفتن اندیس عنصر، به شکل جدیدی تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | هر عنصر از یک دنباله را به‌صورت پروژه می‌کند و توالی‌های حاصل را در یک توالی ترکیب می‌سازد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر پیوسته را از ابتدای یک دنباله عبور می‌دهد و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر پیوسته را از ابتدای یک دنباله برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | یک آرایه از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | یک دنباله را بر اساس پیش‌شرط مشخص شده فیلتر می‌کند. |
|  [List](../../system.collections.generic/list/list/)() | یک فهرست خالی ایجاد می‌کند. |
|  [List](../../system.collections.generic/list/list/)(int) | فهرستی با ظرفیت پیش‌تعریف‌شده ایجاد می‌کند. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | سازندهٔ کپی. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیان lock() در C#. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | یک شیء ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | عملگر انتساب جابجایی. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | عملگر انتساب جابجایی. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | تابع دسترسی. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | تابع دسترسی. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | یک تکرارگر معکوس به آخرین عنصر مجموعه (اولین در معکوس) دریافت می‌کند. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | یک تکرارگر معکوس به آخرین عنصر مجموعهٔ ثابت (اولین در معکوس) دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | اولین نمونهٔ مورد خاص را از فهرست حذف می‌کند. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | تمام عناصری که پیش‌شرط خاصی را برآورده می‌کنند حذف می‌کند. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | موردی را در موقعیت مشخص حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع‌های مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | بردگی از فهرست را حذف می‌کند. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | یک تکرارگر معکوس برای عنصری غیرموجود قبل از شروع مجموعه دریافت می‌کند. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | یک تکرارگر معکوس برای عنصری غیرموجود قبل از شروع مجموعهٔ ثابت دریافت می‌کند. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | ترتیب عناصر کل فهرست را معکوس می‌کند. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | ترتیب عناصر بخش فهرست را معکوس می‌کند. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | ظرفیت فهرست را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای مشترک). امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع‌های مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع‌های مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع‌های مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | عناصر فهرست را مرتب می‌کند. |
| void [Sort](../../system.collections.generic/list/sort/)() | عناصر فهرست را با استفاده از مقایسه‌گر پیش‌فرض مرتب می‌کند. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | عناصر بخش فهرست را مرتب می‌کند. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | عناصر فهرست را مرتب می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | فهرست را به آرایه تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | ظرفیت فهرست را به اندازهٔ آن تنظیم می‌کند. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | تشخیص می‌دهد که آیا هر عنصر در مجموعه با شرایط تعریف‌شده توسط پیش‌شرط مشخص شده مطابقت دارد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازکردن قفل بیان lock() در C#. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | پیاده‌سازی تکرارگر const begin برای محفظهٔ فعلی را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | پیاده‌سازی تکرارگر begin برای محفظهٔ فعلی را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | پیاده‌سازی تکرارگر const end برای محفظهٔ فعلی را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | پیاده‌سازی تکرارگر end برای محفظهٔ فعلی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [X509ExtensionCollection](./x509extensioncollection/)() | یک مجموعهٔ خالی می‌سازد. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | حافظه‌گیر (Destructor). |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [List](../../system.collections.generic/list/)
* فضای نام [System::Security::Cryptography::X509Certificates](../)
* کتابخانه [Aspose.Slides](../../)