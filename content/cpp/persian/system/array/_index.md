---
title: Array
second_title: مرجع API Aspose.Slides برای C++
description: "کلاسی که ساختار داده آرایه را نمایندگی می‌کند. اشیاء این کلاس باید فقط با استفاده از توابع System::MakeArray() و System::MakeObject() ساخته شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/ یا اشکالات تاییدیه می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 14
url: /fa/system/array/
---
## کلاس آرایه

کلاسی که یک ساختار داده آرایه را نشان می‌دهد. اشیای این کلاس باید تنها با استفاده از توابع [System::MakeArray()](../makearray/) و [System::MakeObject()](../makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر یک آرایه |

## متدها

| متد | توضیح |
| --- | --- |
| void [Add](./add/)(const T\&) override | پشتیبانی نمی‌شود زیرا آرایه‌ای که توسط شیء جاری نشان داده می‌شود فقط‌خواند است. |
| [Array](./array/)() | یک آرایه خالی می‌سازد. |
| [Array](./array/)(int, const T\&) | سازندهٔ پرکننده. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | سازندهٔ پرکننده. |
| [Array](./array/)(int, const T) | سازندهٔ پرکننده. |
| [Array](./array/)(**vector_t**\&&) | سازندهٔ جابه‌جایی. |
| [Array](./array/)(const **vector_t**\&) | سازندهٔ کپی. |
| [Array](./array/)(const std::vector\<Q\>\&) | یک شیء [Array](./) می‌سازد و آن را با مقادیری پر می‌کند که از یک شیء std::vector کپی شده‌اند که نوع مقادیر آن همان **T** است ولی متفاوت از **UnderlyingType**. |
| [Array](./array/)(std::vector\<Q\>\&&) | یک شیء [Array](./) می‌سازد و آن را با مقادیری پر می‌کند که از یک شیء std::vector جابه‌جا شده‌اند که نوع مقادیر آن همان **T** است ولی متفاوت از **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | یک شیء [Array](./) می‌سازد و آن را با مقادیری پر می‌کند که از لیست مقداردهی اولیهٔ مشخص‌شده شامل عناصری از نوع **UnderlyingType** دریافت شده است. |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | یک شیء [Array](./) می‌سازد و آن را با مقادیری پر می‌کند که از آرایهٔ مشخص‌شده شامل عناصری از نوع **UnderlyingType** دریافت شده است. |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | یک شیء [Array](./) می‌سازد و آن را با مقادیری پر می‌کند که از لیست مقداردهی اولیهٔ مشخص‌شده شامل عناصری از نوع bool دریافت شده است. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | آرایه را به یک مجموعهٔ فقط‌خواند تبدیل می‌کند. |
| [iterator](./iterator/) [begin](./begin/)() | یک تکرارگر به اولین عنصر container برمی‌گرداند. اگر container خالی باشد، تکرارگر بازگشتی برابر با [end()](./end/) خواهد بود. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | یک تکرارگر به اولین عنصر container با const برمی‌گرداند. اگر container خالی باشد، تکرارگر بازگشتی برابر با [end()](./end/) خواهد بود. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | جستجوی دودویی را در آرایهٔ مرتب‌ شده انجام می‌دهد. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | پیاده‌سازی نشده. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | یک تکرارگر به اولین عنصر const-qualified container برمی‌گرداند. اگر container خالی باشد، تکرارگر بازگشتی برابر با [cend()](./cend/) خواهد بود. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | یک تکرارگر به عنصری که پس از آخرین عنصر container قرار دارد برمی‌گرداند. این عنصر به عنوان یک جایگزین عمل می‌کند؛ تلاش برای دسترسی به آن منجر به رفتار تعریف‌نشده می‌شود. |
| void [Clear](./clear/)() override | پشتیبانی نمی‌شود زیرا آرایه‌ای که توسط شیء جاری نشان داده می‌شود فقط‌خواند است. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | مقادیر **count** را که از ایندکس **startIndex** در آرایهٔ مشخص‌شده شروع می‌شوند، با مقادیر پیش‌فرض جایگزین می‌کند. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | آرایه را کلون می‌کند. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | بازه‌ای از عناصر را از یک [System.Array](./) که از منبع مشخص‌شده شروع می‌شود، کپی می‌کند. |
| **bool** [Contains](./contains/)(const T\&) const override | تعیین می‌کند آیا مورد مشخص‌شده در آرایه وجود دارد یا نه. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | یک شیء جدید [Array](./) می‌سازد و آن را با عناصری از آرایهٔ مشخص‌شده که به نوع **OutputType** تبدیل شده‌اند، با استفاده از delegat تبدیل‌کنندهٔ مشخص‌شده پر می‌کند. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | یک شیء جدید [Array](./) می‌سازد و آن را با عناصری از آرایهٔ مشخص‌شده که به نوع **OutputType** تبدیل شده‌اند، با استفاده از شیء تابع تبدیل‌کنندهٔ مشخص‌شده پر می‌کند. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع به آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از نمای آرایهٔ منبع به آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع به نمای آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از نمای آرایهٔ منبع به نمای آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع روی استک به آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع به آرایهٔ مقصد روی استک کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع روی استک به آرایهٔ مقصد روی استک کپی می‌کند. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع که از اندیس مشخص‌شده شروع می‌شود، به موقعیت مشخص‌شده در آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از نمای آرایهٔ منبع که از اندیس مشخص‌شده شروع می‌شود، به موقعیت مشخص‌شده در آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع که از اندیس مشخص‌شده شروع می‌شود، به موقعیت مشخص‌شده در نمای آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از نمای آرایهٔ منبع که از اندیس مشخص‌شده شروع می‌شود، به موقعیت مشخص‌شده در نمای آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع روی استک که از اندیس مشخص‌شده شروع می‌شود، به موقعیت مشخص‌شده در آرایهٔ مقصد کپی می‌کند. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع که از اندیس مشخص‌شده شروع می‌شود، به موقعیت مشخص‌شده در آرایهٔ مقصد روی استک کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ منبع روی استک که از اندیس مشخص‌شده شروع می‌شود، به موقعیت مشخص‌شده در آرایهٔ مقصد روی استک کپی می‌کند. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | تعداد مشخص‌شده‌ای از عناصر را از نمای آرایهٔ منبع که از اندیس مشخص‌شده شروع می‌شود، به موقعیت مشخص‌شده در آرایهٔ مقصد روی استک کپی می‌کند. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | تمام عناصر آرایهٔ جاری را به آرایهٔ مقصد مشخص‌شده کپی می‌کند. عناصر از ایندکس مشخص‌شده توسط آرگومان arrayIndex در آرایهٔ مقصد درج می‌شوند. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | تمام عناصر آرایهٔ جاری را به آرایهٔ مقصد مشخص‌شده کپی می‌کند. عناصر از ایندکس مشخص‌شده توسط آرگومان dstIndex در آرایهٔ مقصد درج می‌شوند. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | تمام عناصر آرایهٔ جاری را به نمای آرایهٔ مقصد مشخص‌شده کپی می‌کند. عناصر از ایندکس مشخص‌شده توسط آرگومان dstIndex در نمای آرایهٔ مقصد درج می‌شوند. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ جاری که از موقعیت مشخص‌شده شروع می‌شود، به آرایهٔ مقصد مشخص‌شده کپی می‌کند. عناصر از ایندکس مشخص‌شده توسط آرگومان dstIndex در آرایهٔ مقصد درج می‌شوند. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | تعداد مشخص‌شده‌ای از عناصر را از آرایهٔ جاری که از موقعیت مشخص‌شده شروع می‌شود، به نمای آرایهٔ مقصد مشخص‌شده کپی می‌کند. عناصر از ایندکس مشخص‌شده توسط آرگومان dstIndex در نمای آرایهٔ مقصد درج می‌شوند. |
| int [Count](./count/)() const | عدد نمایانگر مجموع تمام عناصر در همهٔ ابعاد آرایه را برمی‌گرداند. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | یک تکرارگر معکوس به اولین عنصر container معکوس‌شده برمی‌گرداند. این به آخرین عنصر container غیرمعکوس‌شده متناظر است. اگر container خالی باشد، تکرارگر بازگشتی برابر با [crend()](./crend/) است. |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | یک تکرارگر معکوس به عنصری که پس از آخرین عنصر container معکوس‌شده قرار دارد برمی‌گرداند. این به عنصری که پیش از اولین عنصر container غیرمعکوس‌شده قرار دارد متناظر است. این عنصر به‌عنوان یک جایگزین عمل می‌کند؛ تلاش برای دسترسی به آن منجر به رفتار تعریف‌نشده می‌شود. |
| **vector_t**\& [data](./data/)() | یک ارجاع به ساختار دادهٔ داخلی مورد استفاده برای ذخیرهٔ عناصر آرایه برمی‌گرداند. |
| const **vector_t**\& [data](./data/)() const | یک ارجاع ثابت به ساختار دادهٔ داخلی مورد استفاده برای ذخیرهٔ عناصر آرایه برمی‌گرداند. |
| vector_t::pointer [data_ptr](./data_ptr/)() | یک اشاره‌گر خام به ابتدای بافر حافظه‌ای که عناصر آرایه در آن ذخیره شده‌اند برمی‌گرداند. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | یک اشاره‌گر خام ثابت به ابتدای بافر حافظه‌ای که عناصر آرایه در آن ذخیره شده‌اند برمی‌گرداند. |
| [iterator](./iterator/) [end](./end/)() | یک تکرارگر به عنصری که پس از آخرین عنصر container قرار دارد برمی‌گرداند. این عنصر به‌عنوان یک جایگزین عمل می‌کند؛ دسترسی به آن منجر به رفتار تعریف‌نشده می‌شود. |
| [const_iterator](./const_iterator/) [end](./end/)() const | یک تکرارگر به عنصری که پس از آخرین عنصر const-qualified container قرار دارد برمی‌گرداند. این عنصر به‌عنوان یک جایگزین عمل می‌کند؛ دسترسی به آن منجر به رفتار تعریف‌نشده می‌شود. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه عدد شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | تشخیص می‌دهد آیا شیٔ [Array](./) مشخص‌شده حاوی عنصری است که الزامات پیش‌شرط مشخص‌شده را برآورده کند. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | به دنبال اولین عنصری در آرایهٔ مشخص‌شده می‌گردد که شرایط پیش‌شرط مشخص‌شده را برآورده کند. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | تمام عناصری را که با شرایط تعریف‌شده توسط پیش‌شرط مشخص‌ شده مطابقت دارند، بازیابی می‌کند. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | به دنبال اولین عنصری در آرایهٔ مشخص‌شده می‌گردد که شرایط پیش‌شرط مشخص‌شده را برآورده کند. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | عملیات مشخص‌شده را بر هر عنصر از آرایهٔ مشخص انجام می‌دهد. |
| int [get_Count](./get_count/)() const override | اندازهٔ آرایه را بازمی‌گرداند. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | بررسی می‌کند آیا مجموعه دارای اندازهٔ ثابت است یا خیر. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | نشان می‌دهد آیا آرایه فقط-خواندنی است یا نه. |
| **int32_t** [get_Length](./get_length/)() const override | یک عدد صحیح ۳۲-بیتی را بازمی‌گرداند که نمایانگر تعداد کل عناصر در همهٔ ابعاد آرایه است. |
| **int64_t** [get_LongLength](./get_longlength/)() const | یک عدد صحیح ۶۴-بیتی را بازمی‌گرداند که نمایانگر تعداد کل عناصر در همهٔ ابعاد آرایه است. |
| **int32_t** [get_Rank](./get_rank/)() const | پیاده‌سازی نشده. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | شیٔی را که از طریق آن مجموعه همگام‌سازی می‌شود دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | یک اشاره‌گر به شیء **Enumerator** بازمی‌گرداند که رابط IEnumerator را برای عناصر آرایهٔ نمایان‌سازی شده توسط شیء فعلی فراهم می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../object/gethashcode/). امکان هش‌گذاری شیءهای سفارشی را فراهم می‌کند. |
| int [GetLength](./getlength/)(int) | تعداد عناصر در بعد مشخص‌شده را بازمی‌گرداند. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | تعداد عناصر در بعد مشخص‌شده را به‌عنوان عدد صحیح ۶۴-بیتی بازمی‌گرداند. |
| int [GetLowerBound](./getlowerbound/)(int) const | حد پایین بعد مشخص‌شده را بازمی‌گرداند. |
| size_t [GetSizeTLength](./getsizetlength/)() const | یک متغیر std::size_t را بازمی‌گرداند که نمایانگر تعداد کل عناصر در همهٔ ابعاد آرایه است. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | حد بالا بعد مشخص‌شده را بازمی‌گرداند. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | سازندهٔ پیش‌فرض. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | سازندهٔ کپی. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | سازندهٔ جابه‌جایی. |
| T [idx_get](./idx_get/)(int) const override | مورد در شاخص مشخص‌شده را بازمی‌گرداند. |
| void [idx_set](./idx_set/)(int, T) override | مقدار مشخص‌شده را به‌عنوان مورد آرایه در شاخص مشخص تنظیم می‌کند. |
| int [IndexOf](./indexof/)(const T\&) const override | شاخص اولین وقوع مورد مشخص‌شده در آرایه را تعیین می‌کند. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | شاخص اولین وقوع مورد مشخص‌شده در آرایه را تعیین می‌کند. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | شاخص اولین وقوع مورد مشخص‌شده در آرایه را از شاخص مشخص‌شده به‌بعد تعیین می‌کند. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | شاخص اولین وقوع مورد مشخص‌شده را در بازه‌ای از موارد آرایه که توسط شاخص شروع و تعداد عناصر در بازه تعیین می‌شود، مشخص می‌کند. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | آرایهٔ نمایان‌سازی‌شده توسط شیء فعلی را با مقادیر آرایهٔ مشخص‌شده پر می‌کند. |
| void [Initialize](./initialize/)() | آرایه را با اشیای ساخته‌شده به‌صورت پیش‌فرض از نوع **T** پر می‌کند. |
| void [Insert](./insert/)(int, const T\&) override | پشتیبانی نمی‌شود زیرا آرایهٔ نمایان‌سازی‌شده توسط شیء فعلی فقط-خواندنی است. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | شاخص آخرین وقوع مورد مشخص‌شده را در بازه‌ای از موارد آرایه که توسط شاخص شروع و تعداد عناصر در بازه تعیین می‌شود، مشخص می‌کند. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | شاخص آخرین وقوع مورد مشخص‌شده را در آرایه از شاخص مشخص‌شده به-بعد تعیین می‌کند. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | شاخص آخرین وقوع مورد مشخص‌شده در آرایه را تعیین می‌کند. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | یک تابع انباشتگر را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا تمام عناصر یک دنباله شرطی را برآورده می‌کنند. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | تعیین می‌کند آیا یک دنباله شامل هر گونه عنصری است. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند آیا هیچ عنصری در دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | میانگین یک دنباله از مقادیر را محاسبه می‌کند که با فراخوانی یک تابع تبدیل بر هر عنصر از دنباله ورودی به‌دست می‌آیند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | دو دنباله را به هم می‌پیوستد. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تعیین می‌کند آیا یک دنباله شامل مقدار مشخص‌شده است. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | تعداد عناصر در دنباله را بازمی‌گرداند (محاسبه‌شده از طریق شمارش مستقیم). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | تعداد عناصری در دنباله که شرط مشخص‌شده را برآورده می‌کنند، بازمی‌گرداند. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | عنصر در شاخص مشخص‌شده در یک دنباله را بازمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | عنصر در شاخص مشخص‌شده در یک دنباله را بازمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | اولین عنصر دنباله را بازمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | اولین عنصر دنباله‌ای که شرط مشخص‌شده را برآورده می‌کند، بازمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | اولین عنصر دنباله را بازمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصر دنباله‌ای که شرطی را برآورده می‌کند را بازمی‌گرداند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | آخرین عنصر دنباله را بازمی‌گرداند. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | آخرین عنصر دنباله را بازمی‌گرداند, یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر از یک دنبالهٔ عمومی فراخوانی می‌کند و حداکثر مقدار حاصل را بازمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر از یک دنبالهٔ عمومی فراخوانی می‌کند و حداقل مقدار حاصل را بازمی‌گرداند. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب صعودی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | عناصر دنباله را به ترتیب نزولی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ترتیب عناصر در یک دنباله را معکوس می‌کند. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر از یک دنباله را به شکل جدیدی تبدیل می‌کند با در نظر گرفتن اندیس عنصر. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | هر عنصر از یک دنباله را پروژه می‌کند و دنباله‌های حاصل را در یک دنباله ترکیب می‌کند. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر متوالی را از ابتدای یک دنباله رد می‌کند و بقیه را بازمی‌گرداند. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | تعدادی مشخص از عناصر متوالی را از ابتدای یک دنباله بازمی‌گرداند. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | آرایه‌ای از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | دنباله‌ای را بر اساس پیش‌شرط مشخص‌شده فیلتر می‌کند. |
| void [Lock](../object/lock/)() | قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../lockcontext/) استفاده کنید. |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | بزرگ‌ترین عنصر آرایه را با استفاده از [operator<()](../operator_less/) برای مقایسهٔ عناصر پیدا می‌کند. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | کوچک‌ترین عنصر آرایه را با استفاده از [operator<()](../operator_less/) برای مقایسهٔ عناصر پیدا می‌کند. |
|  [Object](../object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از کلاس‌های مشتق را فراهم می‌کند. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از کلاس‌های مشتق را فراهم می‌کند. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | عملگر انتساب جابه‌جایی. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | عملگر انتساب جابه‌جایی. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | موردی را در شاخص مشخص‌شده بازمی‌گرداند. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | موردی را در شاخص مشخص‌شده بازمی‌گرداند. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | اشاره‌گری به اولین عنصر آرایهٔ تک‌بعدی بازمی‌گرداند. برای آرایه‌های چندبعدی نتیجه نامشخص است. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | یک iterator معکوس به اولین عنصر محفظهٔ معکوس را بازمی‌گرداند. این به عنصر آخر محفظهٔ غیرمعکوس مربوط می‌شود. اگر محفظه خالی باشد، iterator بازگردانده‌شده برابر با [rend()](./rend/) است. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | یک iterator معکوس به اولین عنصر از محفظه معکوس باز می‌گرداند. این iterator مطابق با آخرین عنصر محفظه غیرمعکوس است. اگر محفظه خالی باشد، iterator بازگشتی برابر با [rend()](./rend/) است. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const&, [ptr](../object/ptr/) const&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)<T>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const&, T const&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)<T>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر اساس ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const&, [String](../string/) const&) | تخصیص خاص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته‌ها. |
| **bool** [Remove](./remove/)(const T&) override | پشتیبانی نمی‌شود زیرا آرایهٔ نمایانده توسط شیء فعلی فقط-خواندنی است. |
| void [RemoveAt](./removeat/)(int) override | پشتیبانی نمی‌شود زیرا آرایهٔ نمایانده توسط شیء فعلی فقط-خواندنی است. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | تعداد شمارنده ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | یک iterator معکوس به عنصری که پس از آخرین عنصر محفظه معکوس قرار دارد بازمی‌گرداند. این iterator مطابق با عنصری است که پیش از اولین عنصر محفظه غیرمعکوس قرار دارد. این عنصر به عنوان یک جای‌دار عمل می‌کند؛ تلاش برای دسترسی به آن رفتار تعریف‌نشده‌ای داشته باشد. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | یک iterator معکوس به عنصری که پس از آخرین عنصر محفظه معکوس قرار دارد بازمی‌گرداند. این iterator مطابق با عنصری است که پیش از اولین عنصر محفظه غیرمعکوس قرار دارد. این عنصر به عنوان یک جای‌دار عمل می‌کند؛ تلاش برای دسترسی به آن رفتار تعریف‌نشده‌ای داشته باشد. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)<[Type](../object/type/)>&, int) | اندازهٔ آرایهٔ مشخص‌شده را به مقدار مشخص‌شده تغییر می‌دهد یا آرایهٔ جدیدی با اندازهٔ مشخص ایجاد می‌کند. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)<[Type](../object/type/)>&) | عناصر آرایهٔ مشخص‌شده را معکوس می‌کند. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)<[Type](../object/type/)>&, int, int) | بازه‌ای از عناصر آرایهٔ مشخص‌شده را معکوس می‌کند. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | آرایه را طوری تنظیم می‌کند که اشاره‌گرهای ذخیره‌شده را به عنوان ضعیف در نظر بگیرد (در صورت امکان). |
| void [SetValue](./setvalue/)(const T&, int) | مقدار عنصر در اندیس مشخص‌شده را تنظیم می‌کند. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)<[Type](../object/type/)>&) | عناصر آرایهٔ مشخص‌شده را با استفاده از مقایسه‌گر پیش‌فرض مرتب می‌کند. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)<[Type](../object/type/)>&, int, int) | بازه‌ای از عناصر آرایهٔ مشخص‌شده را با استفاده از مقایسه‌گر پیش‌فرض مرتب می‌کند. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)<[Type](../object/type/)>&, const [SharedPtr](../sharedptr/)<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)<T>>&) | عناصر آرایهٔ مشخص‌شده را با استفاده از مقایسه‌گر مشخص‌شده مرتب می‌کند. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)<[Type](../object/type/)>&, const [SharedPtr](../sharedptr/)<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)<Y>>&) | اجرا نشده. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)<[Type](../object/type/)>&, const [System::Comparison](../comparison/)<T>&) | عناصر آرایهٔ مشخص‌شده را با استفاده از مقایسهٔ مشخص‌شده مرتب می‌کند. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)<TKey>&, const [ArrayPtr](../arrayptr/)<TValue>&) | دو آرایه را مرتب می‌کند؛ یکی حاوی کلیدها و دیگری حاوی آیتم‌های متناظر، بر پایه مقادیر آرایهٔ حاوی کلیدها، که عناصر آن با استفاده از عملگر < مقایسه می‌شوند. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)<TKey>&, const [ArrayPtr](../arrayptr/)<TValue>&, int, int) | دو آرایه را مرتب می‌کند؛ یکی حاوی کلیدها و دیگری حاوی آیتم‌های متناظر، بر پایه مقادیر آرایهٔ حاوی کلیدها، که عناصر آن با استفاده از مقایسه‌گر پیش‌فرض مقایسه می‌شوند. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | معادل روش C# [Object.ToString()](../object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)<T>, [System::Predicate](../predicate/)<T>) | تعیین می‌کند آیا تمام عناصر آرایهٔ مشخص‌شده شرایط تعریف‌شده توسط پیش‌شرط مشخص را برآورده می‌کنند. |
| static const [TypeInfo](../typeinfo/)& [Type](../object/type/)() | پیاده‌سازی ساختار C# typeof([System.Object](../object/)) را انجام می‌دهد. |
| void [Unlock](../object/unlock/)() | اجرا کردن دستور C# lock() برای باز کردن قفل. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../lockcontext/) استفاده کنید. |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | پیاده‌سازی iterator ثابت begin برای محفظهٔ فعلی را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | پیاده‌سازی iterator begin برای محفظهٔ فعلی را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | پیاده‌سازی iterator ثابت end برای محفظهٔ فعلی را دریافت می‌کند. |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeEndIterator](./virtualizeenditerator/)() override | پیاده‌سازی iterator end برای محفظهٔ فعلی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | تخریب‌کننده. |
| virtual  [~Object](../object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## تعاریف نوع

| نوع تعریف | توضیح |
| --- | --- |
| [ValueType](./valuetype/) | نام مستعار برای نوع عناصر آرایه. |
| [UnderlyingType](./underlyingtype/) | نام مستعار برای نوع مورد استفاده برای نمایاندن هر عنصر آرایه. |
| [EnumerablePtr](./enumerableptr/) | نام مستعار برای نوع اشاره‌گر هوشمند مشترک که به شیء IEnumerable حاوی عناصری از نوع **T** اشاره می‌کند. |
| [EnumeratorPtr](./enumeratorptr/) | نام مستعار برای نوع اشاره‌گر هوشمند مشترک که به شیء IEnumerator حاوی عناصری از نوع **T** اشاره می‌کند. |
| [iterator](./iterator/) | نوع iterator. |
| [const_iterator](./const_iterator/) | نوع iterator ثابت. |
| [reverse_iterator](./reverse_iterator/) | نوع iterator معکوس. |
| [const_reverse_iterator](./const_reverse_iterator/) | نوع iterator ثابت معکوس. |

## ملاحظات

```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // ایجاد و پر کردن آرایه.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // چاپ موارد آرایه.
  Print(arrayPtr);

  // مرتب‌سازی موارد آرایه به صورت صعودی.
  Array<int32_t>::Sort(arrayPtr);

  // چاپ موارد آرایه.
  Print(arrayPtr);

  // چاپ تعداد موارد آرایه.
  std::cout << arrayPtr->get_Length() << std::endl;

  // چاپ ایندکس موردی که برابر با ۴ است.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // تغییر اندازه آرایه.
  Array<int32_t>::Resize(arrayPtr, 3);

  // چاپ موارد آرایه.
  Print(arrayPtr);

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## همچنین ببینید

* کلاس [ArrayBase](../arraybase/)
* کلاس [IList](../../system.collections.generic/ilist/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)