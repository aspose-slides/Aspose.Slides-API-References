---
title: TimeSpan
second_title: مرجع API Aspose.Slides برای C++
description: "نمایش یک بازهٔ زمانی. این نوع باید بر روی پشته تخصیص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 1314
url: /fa/system/timespan/
---
## کلاس TimeSpan

یک بازهٔ زمانی را نمایندگی می‌کند. این نوع باید بر روی پشته تخصیص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class TimeSpan
```

## متدها

| Method | Description |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | یک نمونهٔ جدید از کلاس [TimeSpan](./) برمی‌گرداند که یک بازهٔ زمانی را نشان می‌دهد که مجموع بازه‌های زمانی نشان داده شده توسط شیء فعلی و شیء مشخص‌شده است. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | دو شیء [TimeSpan](./) را مقایسه می‌کند. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | شیء فعلی و شیء مشخص‌شده را مقایسه می‌کند. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | شیء فعلی و شیء مشخص‌شده را مقایسه می‌کند. |
| [TimeSpan](./) [Duration](./duration/)() const | یک نمونهٔ جدید از شیء [TimeSpan](./) برمی‌گرداند که مقدار آن مقدار مطلق شیء فعلی است. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | تعیین می‌کند که آیا بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی برابر با بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده است. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | تعیین می‌کند که آیا بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی برابر با بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده است. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | اگر اشیاء مشخص‌شده همان بازهٔ زمانی را نمایندگی کنند true برمی‌گرداند، در غیر اینصورت false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | یک شیء جدید [TimeSpan](./) برمی‌گرداند که بازهٔ مشخص‌شده را نمایندگی می‌کند. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | یک شیء جدید [TimeSpan](./) برمی‌گرداند که بازهٔ مشخص‌شده را نمایندگی می‌کند. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | یک شیء جدید [TimeSpan](./) برمی‌گرداند که بازهٔ مشخص‌شده را نمایندگی می‌کند. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | یک شیء جدید [TimeSpan](./) برمی‌گرداند که بازهٔ مشخص‌شده را نمایندگی می‌کند. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | یک شیء جدید [TimeSpan](./) برمی‌گرداند که بازهٔ مشخص‌شده را نمایندگی می‌کند. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | یک شیء جدید [TimeSpan](./) برمی‌گرداند که بازهٔ مشخص‌شده را نمایندگی می‌کند. |
| constexpr int [get_Days](./get_days/)() const | جزء روزهای بازهٔ زمانی نشان‌داده‌شده توسط شیء [TimeSpan](./) فعلی را برمی‌گرداند. |
| constexpr int [get_Hours](./get_hours/)() const | جزء ساعت‌های بازهٔ زمانی نشان‌داده‌شده توسط شیء [TimeSpan](./) فعلی را برمی‌گرداند. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | جزء میلی‌ثانیه‌های بازهٔ زمانی نشان‌داده‌شده توسط شیء [TimeSpan](./) فعلی را برمی‌گرداند. |
| constexpr int [get_Minutes](./get_minutes/)() const | جزء دقیقّه‌های بازهٔ علمی نشان‌داده‌شده توسط شیء [TimeSpan](./) فعلی را برمی‌گرداند. |
| constexpr int [get_Seconds](./get_seconds/)() const | جزء ثانیه‌های بازهٔ زمانی نشان‌داده‌شده توسط شیء [TimeSpan](./) فعلی را برمی‌گرداند. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | تعداد فواصل ۱۰۰-نانوثانیه‌ای که بازهٔ زمانی نشان‌داده‌شده توسط شیء [TimeSpan](./) فعلی را تشکیل می‌دهند را برمی‌گرداند. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | مقدار شیء [TimeSpan](./) فعلی را که به روزهای کامل و کسری بیان می‌شود، برمی‌گرداند. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | مقدار شیء [TimeSpan](./) فعلی را که به ساعت‌های کامل و کسری بیان می‌شود، برمی‌گرداند. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | مقدار شیء [TimeSpan](./) فعلی را که به میلی‌ثانیه‌های کامل و کسری بیان می‌شود، برمی‌گرداند. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | مقدار شیء [TimeSpan](./) فعلی را که به دقیقّه‌های کامل و کسری بیان می‌شود، برمی‌گرداند. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | مقدار شیء [TimeSpan](./) فعلی را که به ثانیه‌های کامل و کسری بیان می‌شود، برمی‌گرداند. |
| int [GetHashCode](./gethashcode/)() const | یک کد هش برای شیء فعلی برمی‌گرداند. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | یک نمونهٔ جدید از شیء [TimeSpan](./) برمی‌گرداند که مقدار منفی نشان‌داده‌شده توسط شیء [TimeSpan](./) فعلی را نمایندگی می‌کند. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | تعیین می‌کند که آیا بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی برابر با بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده نیست. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | یک نمونهٔ جدید از کلاس [TimeSpan](./) برمی‌گرداند که یک بازهٔ زمانی را نشان می‌دهد که مجموع بازه‌های زمانی نشان داده شده توسط شیء فعلی و شیء مشخص‌شده است. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | خود شیء را برمی‌گرداند. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | به شیء فعلی بازهٔ زمانی که مجموع بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی و شیء مشخص‌شده است اختصاص می‌دهد. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | یک نمونهٔ جدید از کلاس [TimeSpan](./) برمی‌گرداند که یک بازهٔ زمانی را نشان می‌دهد که نتیجهٔ تفریق بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده از بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی است. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | یک نمونهٔ جدید از شیء [TimeSpan](./) برمی‌گرداند که مقدار منفی نشان‌داده‌شده توسط شیء [TimeSpan](./) فعلی را نمایندگی می‌کند. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | به شیء فعلی بازهٔ زمانی که نتیجهٔ تفریق بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده از بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی است اختصاص می‌دهد. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | تعیین می‌کند که آیا بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی کوتاه‌تر از بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده است. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | تعیین می‌کند که آیا بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی کوتاه‌تر یا برابر با بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده است. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | بازهٔ زمانی نشان‌داده‌شده توسط شیء [TimeSpan](./) مشخص‌شده را به شیء [TimeSpan](./) فعلی اختصاص می‌دهد. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | تعیین می‌کند که آیا بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی برابر با بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده است. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | تعیین می‌کند که آیا بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی طولانی‌تر از بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده است. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | تعیین می‌کند که آیا بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی طولانی‌تر یا برابر با بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده است. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند با استفاده از فراهم‌کنندهٔ قالب‌گذاری مشخص‌شده. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند با استفاده از قالب‌های مشخص‌شده، فراهم‌کنندهٔ قالب‌گذاری و سبک‌ها. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند با استفاده از قالب، فراهم‌کنندهٔ قالب‌گذاری و سبک‌ها. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | یک نمونهٔ جدید از کلاس [TimeSpan](./) برمی‌گرداند که یک بازهٔ زمانی را نشان می‌دهد که نتیجهٔ تفریق بازهٔ زمانی نشان‌داده‌شده توسط شیء مشخص‌شده از بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی است. |
| constexpr [TimeSpan](./timespan/)() | یک شیء [TimeSpan](./) می‌سازد که بازهٔ زمانی صفر را نمایندگی می‌کند. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | یک نمونهٔ کلاس [TimeSpan](./) می‌سازد که بازهٔ زمانی مشخص‌شده را نمایندگی می‌کند. |
| [TimeSpan](./timespan/)(int, int, int) | یک نمونهٔ کلاس [TimeSpan](./) می‌سازد که بازهٔ زمانی را که برابر با مجموع ساعت‌ها، دقیقّه‌ها و ثانیه‌های مشخص‌شده است، نمایندگی می‌کند. |
| [TimeSpan](./timespan/)(int, int, int, int, int) | یک نمونهٔ کلاس [TimeSpan](./) می‌سازد که بازهٔ زمانی را که برابر با مجموع ساعت‌ها، دقیقّه‌ها، ثانیه‌ها و میلی‌ثانیه‌های مشخص‌شده است، نمایندگی می‌کند. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | یک شیء [TimeSpan](./) می‌سازد که بازهٔ زمانی برابر با بازهٔ زمانی نشان‌داده‌شده توسط شیء [TimeSpan](./) مشخص‌شده است. |
| [String](../string/) [ToString](./tostring/)() const | نمایش رشته‌ای بازهٔ زمانی نشان‌داده‌شده توسط شیء فعلی را برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | مقدار شیء فعلی را به نمایش رشته‌ای معادل تبدیل می‌کند، با استفاده از قالب مشخص‌شده. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | مقدار شیء فعلی را به نمایش رشته‌ای معادل تبدیل می‌کند، با استفاده از قالب و فراهم‌کنندهٔ قالب‌گذاری مشخص‌شده. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند و نتیجهٔ تبدیل را برمی‌گرداند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند با استفاده از فراهم‌کنندهٔ قالب‌گذاری مشخص‌شده و نتیجهٔ تبدیل را برمی‌گرداند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند با استفاده از قالب‌های مشخص‌شده و فراهم‌کنندهٔ قالب‌گذاری، و نتیجهٔ تبدیل را برمی‌گرداند. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند با استفاده از قالب، فراهم‌کنندهٔ قالب‌گذاری و سبک‌های مشخص‌شده، و نتیجهٔ تبدیل را برمی‌گرداند. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند با استفاده از قالب‌های مشخص‌شده، فراهم‌کنندهٔ قالب‌گذاری و سبک‌ها، و نتیجهٔ تبدیل را برمی‌گرداند. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | رشته را به شیء معادل [TimeSpan](./) تبدیل می‌کند با استفاده از قالب و فراهم‌کنندهٔ قالب‌گذاری، و نتیجهٔ تبدیل را برمی‌گرداند. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | یک شیء [TypeInfo](../typeinfo/) برمی‌گرداند که ساختار [TimeSpan](./) را نمایندگی می‌کند. |

## فیلدها

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | شیء [TimeSpan](./) که طولانی‌ترین بازه ممکن را نمایندگی می‌کند. |
| static [MinValue](./minvalue/) | /// شیء [TimeSpan](./) که کوتاه‌ترین بازه ممکن را نمایندگی می‌کند. |
| static constexpr [TicksPerDay](./ticksperday/) | تعداد فواصل ۱۰۰-نانوثانیه‌ای در یک روز (بازهٔ ۲۴ ساعته). |
| static constexpr [TicksPerHour](./ticksperhour/) | تعداد فواصل ۱۰۰-نانوثانیه‌ای در یک ساعت. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | تعداد فواصل ۱۰۰-نانوثانیه‌ای در یک میلی‌ثانیه. |
| static constexpr [TicksPerMinute](./ticksperminute/) | تعداد فواصل ۱۰۰-نانوثانیه‌ای در یک دقیقه. |
| static constexpr [TicksPerSecond](./tickspersecond/) | تعداد فواصل ۱۰۰-نانوثانیه‌ای در یک ثانیه. |
| static [Zero](./zero/) | شیء [TimeSpan](./) که بازهٔ صفر را نمایندگی می‌کند. |

## توضیحات

```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
تعداد تیک‌ها: 260928000000000
تعداد میلی‌ثانیه‌ها: 0
کل تعداد میلی‌ثانیه‌ها: 2.60928e+10
تعداد دقیقه‌ها: 0
کل تعداد دقیقه‌ها: 434880
تعداد ساعت‌ها: 0
کل تعداد ساعت‌ها: 0
تعداد روزها: 302
کل تعداد روزها: 302
*/
```

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)