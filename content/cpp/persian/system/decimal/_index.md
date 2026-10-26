---
title: Decimal
second_title: Aspose.Slides برای C++ مرجع API
description: "یک عدد اعشاری را نشان می‌دهد. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 261
url: /fa/system/decimal/
---
## کلاس Decimal

یک عدد اعشاری را نشان می‌دهد. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class Decimal
```

## متدها

| متد | توضیح |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | دو مقدار [Decimal](./) مشخص را اضافه می‌کند. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | کوچک‌ترین مقدار صحیح که بزرگ یا مساوی مقدار مشخص شده باشد را برمی‌گرداند. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | تعیین می‌کند که آیا مقدار نمایان شده توسط شیء [Decimal](./) اول کمتر، مساوی یا بزرگتر از مقداری است که توسط شیء [Decimal](./) دوم نمایان شده است. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری کمتر، مساوی یا بزرگتر از مقدار نمایان شده توسط شیء مشخص شده است. |
|  [Decimal](./decimal/)() | یک نمونه‌ای که نمایانگر 0 است ایجاد می‌کند. |
|  [Decimal](./decimal/)(std::int8_t) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(std::int16_t) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(std::int32_t) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(std::int64_t) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(std::uint8_t) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(std::uint16_t) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(std::uint32_t) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(std::uint64_t) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(**float**) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(**double**) | یک نمونه‌ای که نمایانگر مقدار مشخص شده است ایجاد می‌کند. |
| explicit  [Decimal](./decimal/)(const std::string\&) | یک نمونه‌ای که نمایانگر مقداری است که نمایش رشته‌ای آن به عنوان یک شیء از کلاس std::string مشخص شده است ایجاد می‌کند. |
|  [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | یک شیء [Decimal](./) را از اجزاء مشخص شده ساخته می‌کند. |
|  [Decimal](./decimal/)(const [Decimal](./)\&) | یک نمونه از کلاس [Decimal](./) که همان عدد را که شیء [Decimal](./) مشخص نمایان می‌کند، ایجاد می‌کند. |
|  [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | یک نمونه از کلاس [Decimal](./) را از آرایه‌ی صحیحی که حاوی نمایش باینری است، می‌سازد. |
|  [Decimal](./decimal/)(std::nullptr_t) | همواره ArgumentNullException را پرتاب می‌کند. |
|  [Decimal](./decimal/)(const [number_type](./number_type/)\&) | یک نمونه از کلاس [Decimal](./) که نمایانگر مقدار مشخص شده است، می‌سازد. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | دو مقدار [Decimal](./) مشخص را تقسیم می‌کند. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | تعیین می‌کند که آیا مقادیر نمایان شده توسط شیء جاری و شیء مشخص شده برابر هستند. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | تعیین می‌کند که آیا مقادیر نمایان شده توسط شیء جاری و شیء مشخص شده برابر هستند. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | تعیین می‌کند که آیا مقادیر نمایان شده توسط اشیاء مشخص برابر هستند. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | بزرگ‌ترین مقدار صحیح که کمتر یا مساوی مقدار مشخص شده باشد را برمی‌گرداند. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) مقدار OLE currency مشخص به مقدار معادل [Decimal](./). پیاده‌سازی نشده. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | شیء [Decimal](./) مشخص را به نمایش باینری مقدار نمایان شده توسط آن تبدیل می‌کند. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) مقدار [Decimal](./) مشخص را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| int [GetHashCode](./gethashcode/)() const | کد هش برای شیء جاری را برمی‌گرداند. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | کد نوع شیء را دریافت می‌کند. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | دو مقدار [Decimal](./) مشخص را ضرب می‌کند. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | یک نمونه جدید از کلاس [Decimal](./) که نمایانگر مقداری است که از نفی مقدار نمایان شده توسط شیء مشخص به دست می‌آید، برمی‌گرداند. |
| explicit  [operator bool](./operator_bool/)() const | مقدار نمایان شده توسط شیء جاری را به مقدار بولی تبدیل می‌کند. |
| explicit  [operator double](./operator_double/)() const | مقدار نمایان شده توسط شیء جاری را به مقدار عدد نقطه شناور دوگانه دقت تبدیل می‌کند. |
| explicit  [operator float](./operator_float/)() const | مقدار نمایان شده توسط شیء جاری را به مقدار عدد نقطه شناور تک دقت تبدیل می‌کند. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | تعیین می‌کند که آیا مقادیر نمایان شده توسط شیء جاری و شیء مشخص شده برابر نیستند. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری متفاوت از 0 است. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | یک نمونه جدید از کلاس [Decimal](./) که نمایانگر مقداری است که نتیجه عمل باقی‌مانده (modulo) بین مقادیر نمایان شده توسط شیء جاری و شیء مشخص است، برمی‌گرداند. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | به شیء جاری مقدار جدیدی که نتیجهٔ عمل modulo بین مقادیر نمایان شده توسط شیء جاری و شیء مشخص است اختصاص می‌دهد. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | یک نمونه جدید از کلاس [Decimal](./) که نمایانگر مقداری است که نتیجهٔ ضرب مقادیر نمایان شده توسط شیء جاری و شیء مشخص است، برمی‌گرداند. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | به شیء جاری مقدار جدیدی که نتیجهٔ ضرب مقادیر نمایان شده توسط شیء جاری و شیء مشخص است اختصاص می‌دهد. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | یک نمونه جدید از کلاس [Decimal](./) که نمایانگر مقداری است که مجموع مقادیر نمایان شده توسط شیء جاری و شیء مشخص است، برمی‌گرداند. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | مقدار نمایان شده توسط شیء جاری را افزایش می‌دهد. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | به شیء جاری مقدار جدیدی که مجموع مقادیر نمایان شده توسط شیء جاری و شیء مشخص است اختصاص می‌دهد. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | یک نمونه جدید از کلاس [Decimal](./) که نمایانگر مقداری است که نتیجهٔ تفریق مقدار نمایان شده توسط شیء مشخص از مقدار نمایان شده توسط شیء جاری است، برمی‌گرداند. |
| [Decimal](./) [operator-](./operator_minus/)() const | یک نمونه جدید از کلاس [Decimal](./) که نمایانگر مقداری است که از نفی مقدار نمایان شده توسط شیء جاری به دست می‌آید، برمی‌گرداند. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | مقدار نمایان شده توسط شیء جاری را کاهش می‌دهد. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | به شیء جاری مقدار جدیدی که نتیجهٔ تفریق مقدار نمایان شده توسط شیء مشخص از مقدار نمایان شده توسط شیء جاری است اختصاص می‌دهد. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | یک نمونه جدید از کلاس [Decimal](./) که نمایانگر مقداری است که نتیجهٔ تقسیم مقدار نمایان شده توسط شیء جاری بر مقدار نمایان شده توسط شیء مشخص است، برمی‌گرداند. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | به شیء جاری مقدار جدیدی که نتیجهٔ تقسیم مقدار نمایان شده توسط شیء جاری بر مقدار نمایان شده توسط شیء مشخص است اختصاص می‌دهد. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری کمتر از مقدار نمایان شده توسط شیء مشخص است. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری کمتر یا مساوی مقدار نمایان شده توسط شیء مشخص است. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | مقدار نمایان شده توسط شیء مشخص را به شیء جاری اختصاص می‌دهد. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | تعیین می‌کند که آیا مقادیر نمایان شده توسط شیء جاری و شیء مشخص برابر هستند. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری 0 است. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری بزرگتر از مقدار نمایان شده توسط شیء مشخص است. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری بزرگتر یا مساوی مقدار نمایان شده توسط شیء مشخص است. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | نمایش رشته‌ای یک عدد اعشاری را به یک نمونه معادل از کلاس [Decimal](./) تبدیل می‌کند. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | نمایش رشته‌ای یک عدد اعشاری را با استفاده از سبک مشخص به یک نمونه معادل از کلاس [Decimal](./) تبدیل می‌کند. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | نمایش رشته‌ای یک عدد اعشاری را با استفاده از فراهم‌کننده قالب مشخص به یک نمونه معادل از کلاس [Decimal](./) تبدیل می‌کند. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | نمایش رشته‌ای یک عدد اعشاری را با استفاده از سبک و فراهم‌کننده قالب مشخص به یک نمونه معادل از کلاس [Decimal](./) تبدیل می‌کند. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | باقی‌ماندهٔ تقسیم دو مقدار [Decimal](./) را محاسبه می‌کند. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | مقدار مشخص شده را به نزدیک‌ترین عدد صحیح رند می‌کند. یک پارامتر رفتار تابع را وقتی که مقدار مشخص شده به دو عدد نزدیک برابر باشد تعیین می‌کند. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | مقدار مشخص شده را به نزدیک‌ترین مقدار با تعداد رقم اعشاری مشخص رند می‌کند. یک پارامتر رفتار تابع را وقتی که مقدار مشخص شده به دو عدد نزدیک برابر باشد تعیین می‌کند. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | یک مقدار [Decimal](./) مشخص را از مقدار دیگر کم می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | مقدار [Decimal](./) را به مقدار صحیح بدون علامت 8 بیتی تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | مقدار [Decimal](./) را به عدد نقطه شناور دوگانه دقت تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | مقدار [Decimal](./) را به عدد صحیح 16 بیتی تبدیل می‌کند. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | مقدار [Decimal](./) را به عدد صحیح 32 بیتی تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | مقدار [Decimal](./) را به عدد صحیح 64 بیتی تبدیل می‌کند. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) مقدار [Decimal](./) مشخص را به مقدار معادل OLE currency تبدیل می‌کند. پیاده‌سازی نشده. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | مقدار [Decimal](./) را به عدد صحیح 8 بیتی تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | مقدار [Decimal](./) را به عدد نقطه شناور تک دقت تبدیل می‌کند. |
| std::string [ToStdString](./tostdstring/)() const | یک نمونهٔ std::string که شامل نمایش رشته‌ای مقدار نمایان شده توسط شیء است را برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)() const | نمایش رشته‌ای مقدار نمایان شده توسط شیء را برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | شیء جاری را با استفاده از اطلاعات قالب‌گیری مخصوص فرهنگ، به رشته تبدیل می‌کند. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | شیء جاری را به نمایش رشته‌ای خود با استفاده از قالب رشته‌ای مشخص و اطلاعات قالب‌گیری مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) مشخص تبدیل می‌کند. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | نمایش رشته‌ای مقدار نمایان شده توسط شیء را برمی‌گرداند. برای استفاده داخلی. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | مقدار [Decimal](./) را به مقدار صحیح بدون علامت 16 بیتی تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | مقدار [Decimal](./) را به مقدار صحیح بدون علامت 32 بیتی تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | مقدار [Decimal](./) را به مقدار صحیح بدون علامت 64 بیتی تبدیل می‌کند. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | شیء [Decimal](./) را که نمایانگر مقداری است که بخش صحیح آن برابر با مقدار نمایان شده توسط شیء [Decimal](./) مشخص است و تمام ارقام کسری حذف شده‌اند، برمی‌گرداند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | رشتهٔ مشخص حاوی نمایش رشته‌ای یک عدد را به مقدار معادل [Decimal](./) تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | رشتهٔ مشخص حاوی نمایش رشته‌ای یک عدد را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده، به مقدار معادل [Decimal](./) تبدیل می‌کند. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | یک ارجاع به شیء [TypeInfo](../typeinfo/) که اطلاعات نوع کلاس [Decimal](./) را نشان می‌دهد، برمی‌گرداند. |
|  [~Decimal](./~decimal/)() | Destructor. |
## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [MaxValue](./maxvalue/) | بزرگ‌ترین عددی که می‌تواند توسط کلاس [Decimal](./) نمایان شود را نشان می‌دهد. |
| static [MinusOne](./minusone/) | عدد -1 را نشان می‌دهد. |
| static [MinValue](./minvalue/) | کوچک‌ترین عددی که می‌تواند توسط کلاس [Decimal](./) نمایان شود را نشان می‌دهد. |
| static [One](./one/) | عدد 1 را نشان می‌دهد. |
| static [Zero](./zero/) | عدد 0 را نشان می‌دهد. |
## نوع‌تعاریف

| نوع‌تعریف | توضیح |
| --- | --- |
| [number_type](./number_type/) | یک نام مستعار برای Detail::decimal_number_type است. |
## توضیحات

```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)