---
title: DateTime
second_title: مرجع API Aspose.Slides برای C++
description: "یک مقدار تاریخ و زمان خاص را بر روی پیوست زمانی نشان می‌دهد. این نوع باید بر روی پشته تخصیص داده شود و به توابع به صورت مقدار یا ارجع پاس شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 222
url: /fa/system/datetime/
---
## کلاس DateTime

یک مقدار تاریخ و زمان خاص بر روی kontinuum زمان را نشان می‌دهد. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیای این نوع استفاده نکنید.

```cpp
class DateTime
```

## متدها

| متد | توضیح |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان حاصل از افزودن بازه زمانی مشخص به مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری را نشان می‌دهد. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان را نشان می‌دهد که مجموع مقدار نمایان‌شده توسط شیء جاری و تعداد روزهای مشخص شده است. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان را نشان می‌دهد که مجموع مقدار نمایان‌شده توسط شیء جاری و تعداد ساعت‌های مشخص شده است. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان را نشان می‌دهد که مجموع مقدار نمایان‌شده توسط شیء جاری و تعداد میلی‌ثانیه‌های مشخص شده است. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان را نشان می‌دهد که مجموع مقدار نمایان‌شده توسط شیء جاری و تعداد دقیقه‌های مشخص شده است. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان را نشان می‌دهد که مجموع مقدار نمایان‌شده توسط شیء جاری و تعداد ماه‌های مشخص شده است. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان را نشان می‌دهد که مجموع مقدار نمایان‌شده توسط شیء جاری و تعداد ثانیه‌های مشخص شده است. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان را نشان می‌دهد که مجموع مقدار نمایان‌شده توسط شیء جاری و تعداد فواصل ۱۰۰ نانوثانیهٔ مشخص شده است. |
| [DateTime](./) [AddYears](./addyears/)(int) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان برابر با مقدار نمایان‌شده توسط شیء جاری است، با این تفاوت که مولفهٔ سال آن به میزان عدد مشخص شده افزایش یافته است. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | دو مقدار نمایان‌شده توسط نمونه‌های مشخص‌شده از کلاس [DateTime](./) را مقایسه می‌کند و مقداری را برمی‌گرداند که موقعیت نسبی مقادیر را بر روی خط زمان نشان می‌دهد. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | دو مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری و نمونهٔ مشخص‌شده از کلاس [DateTime](./) را مقایسه می‌کند و مقداری را برمی‌گرداند که موقعیت نسبی مقادیر را بر روی خط زمان نشان می‌دهد. |
| constexpr [DateTime](./datetime/)() | یک نمونه را می‌سازد که کوچک‌ترین مقدار ممکن تاریخ و زمان برابر با MinValue را نشان می‌دهد. |
|  [DateTime](./datetime/)(int, int, int) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس سال، ماه و روز مشخصی نشان می‌دهد. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس سال، ماه و روز مشخصی در تقویم مشخص‌شده نشان می‌دهد. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس سال، ماه، روز، ساعت، دقیقه و ثانیه مشخصی نشان می‌دهد. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس سال، ماه، روز، ساعت، دقیقه و ثانیه مشخصی نشان می‌دهد. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس سال، ماه، روز، ساعت، دقیقه و ثانیه مشخصی در تقویم مشخص‌شده نشان می‌دهد. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس سال، ماه، روز، ساعت، دقیقه، ثانیه و میلی‌ثانیه مشخصی نشان می‌دهد. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس سال، ماه، روز، ساعت، دقیقه، ثانیه و میلی‌ثانیه مشخصی در تقویم مشخص‌شده نشان می‌دهد. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس تعداد تیک‌ها نشان می‌دهد. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | یک نمونه را می‌سازد که مقدار تاریخ و زمان را بر اساس تعداد تیک‌ها نشان می‌دهد. برای استفاده داخلی. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | یک نمونه را به صورت کپی‌ساز می‌سازد. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | تعداد روزهای ماه مشخص‌شده از سال مشخص‌شده را برمی‌گرداند. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | تعیین می‌کند که آیا نمونه‌های مشخص‌شده از کلاس [DateTime](./) مقدار تاریخ و زمان یکسانی را نشان می‌دهند یا نه. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | تعیین می‌کند که آیا نمونهٔ مشخص‌شده از کلاس [DateTime](./) مقدار تاریخ و زمان یکسانی با شیء جاری دارد یا نه. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | مقدار تاریخ-زمان را از عدد صحیح ۶۴-بیتی بدون علامت مشخص‌شده تجزیه می‌کند و نمونهٔ جدید کلاس [DateTime](./) را به آن مقدار تنظیم می‌سد. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | زمان فایل مشخص‌شده را به یک نمونه از کلاس [DateTime](./) تبدیل می‌کند که مقدار تاریخ و زمان یکسانی را به عنوان زمان محلی نشان می‌دهد. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | زمان فایل مشخص‌شده را به یک نمونه از کلاس [DateTime](./) تبدیل می‌کند که مقدار تاریخ و زمان یکسانی را به عنوان زمان UTC نشان می‌دهد. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | یک نمونه از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان معادل با تاریخ OLE Automation مشخص‌شده را نشان می‌دهد. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | مقدار زمان یونیکس مشخص‌شده را به یک نمونه از کلاس [DateTime](./) تبدیل می‌کند. برای استفاده داخلی. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که بخش تاریخ مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری را نشان می‌دهد و هر مؤلفهٔ بخش زمان را برابر ۰ قرار می‌دهد. |
| int [get_Day](./get_day/)() const | شمارهٔ ترتیبی روز در ماه نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | مقداری را برمی‌گرداند که نمایانگر روز هفته‌ای است که توسط شیء جاری نشان داده می‌شود. |
| int [get_DayOfYear](./get_dayofyear/)() const | شمارهٔ ترتیبی روز در سال نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| constexpr int [get_Hour](./get_hour/)() const | مؤلفهٔ ساعت مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | مقداری را برمی‌گرداند که نشان می‌دهد تاریخ و زمان نمایان‌شده توسط شیء جاری، تاریخ و زمان محلی، UTC یا هیچ‌کدام است. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | مؤلفهٔ میلی‌ثانیه مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| constexpr int [get_Minute](./get_minute/)() const | مؤلفهٔ دقیقه مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| int [get_Month](./get_month/)() const | شمارهٔ ترتیبی ماه در سال نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| static [DateTime](./) [get_Now](./get_now/)() | یک نمونه از کلاس [DateTime](./) برمی‌گرداند که زمان جاری را به صورت زمان محلی نشان می‌دهد. |
| constexpr int [get_Second](./get_second/)() const | مؤلفهٔ ثانیه مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | تعداد فواصل ۱۰۰ نانوثانیه‌ای که از ساعت 0:00:00 UTC، 1 ژانویه 0001 در تقویم گرجی تا تاریخ و زمان نمایان‌شده توسط شیء جاری گذشته است را برمی‌گرداند. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | مقداری را برمی‌گرداند که بازهٔ زمانی از ابتدای روز نمایان‌شده توسط شیء جاری تا مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری را نشان می‌دهد. |
| static [DateTime](./) [get_Today](./get_today/)() | یک نمونه از کلاس [DateTime](./) برمی‌گرداند که تاریخ جاری را نشان می‌دهد به‌طوری که هر مؤلفهٔ بخش زمان مقدار نمایان‌شده توسط شیء برابر ۰ باشد. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | یک نمونه از کلاس [DateTime](./) برمی‌گرداند که زمان جاری را به صورت UTC نشان می‌دهد. |
| int [get_Year](./get_year/)() const | سال نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | اجزای تاریخ را دریافت می‌کند. برای استفاده داخلی. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | آرایه‌ای از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای شیء جاری است که با یکی از نمادهای استاندارد قالب‌بندی تاریخ و زمان فرمت شده است. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | آرایه‌ای از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای شیء جاری است که با نماد قالب‌بندی استاندارد تاریخ و زمان مشخص شده فرمت شده است. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | آرایه‌ای از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای شیء جاری است که با یکی از نمادهای استاندارد قالب‌بندی تاریخ و زمان و فراهم‌کنندهٔ قالب مشخص شده فرمت شده است. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | آرایه‌ای از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای شیء جاری است که با نماد قالب‌بندی استاندارد تاریخ و زمان و فراهم‌کنندهٔ قالب مشخص شده فرمت شده است. |
| int [GetHashCode](./gethashcode/)() const | کد هش برای شیء جاری را برمی‌گرداند. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | تعیین می‌کند که آیا مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری در بازهٔ ساعت تابستانی برای منطقه زمانی جاری قرار دارد یا خیر. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | تعیین می‌کند که آیا سال مشخص‌شده سال کبیسه است یا نه. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | تعیین می‌کند که آیا شیء جاری و شیء [DateTime](./) مشخص‌شده، مقادیر تاریخ و زمان متفاوتی را نشان می‌دهند یا نه. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان حاصل از جمع مقدار نمایان‌شده توسط شیء جاری و بازه زمانی مشخص‌شده را نشان می‌دهد. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | شیء جاری را به مقدار تاریخ و زمان حاصل از جمع مقدار نمایان‌شده توسط شیء جاری و بازه زمانی مشخص‌شده تنظیم می‌کند. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | یک نمونه جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان حاصل از کم کردن بازه زمانی مشخص‌شده از مقدار نمایان‌شده توسط شیء جاری را نشان می‌دهد. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | یک نمونه از کلاس [TimeSpan](../timespan/) برمی‌گرداند که بازهٔ زمانی بین مقادیر تاریخ و زمان نمایان‌شده توسط شیء جاری و شیء مشخص‌شده را نشان می‌دهد. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | شیء جاری را به مقدار تاریخ و زمان حاصل از کم کردن بازه زمانی مشخص‌شده از مقدار تاریخ و زمان نمایان‌شده توسط شیء جاری تنظیم می‌کند. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | تعیین می‌کند که آیا شیء جاری مقداری از تاریخ و زمان دارد که قبل از مقدار نمایان‌شده توسط شیء [DateTime](./) مشخص‌شده است یا خیر. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | تعیین می‌کند که آیا شیء جاری مقدار تاریخ و زمان دارد که قبل یا مساوی مقدار نمایان‌شده توسط شیء [DateTime](./) مشخص‌شده است یا خیر. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | مقدار نمایان‌شده توسط نمونهٔ [DateTime](./) مشخص‌شده را به شیء جاری اختصاص می‌دهد. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | تعیین می‌کند که آیا شیء جاری و شیء [DateTime](./) مشخص‌شده، مقدار تاریخ و زمان یکسانی را نشان می‌دهند یا نه. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | مشخص می‌کند که آیا شیء فعلی نمایانگر مقدار تاریخ و زمان است که پس از مقداری که توسط شیء [DateTime](./) مشخص شده است. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | مشخص می‌کند که آیا شیء فعلی نمایانگر مقدار تاریخ و زمان است که پس از یا برابر با مقداری که توسط شیء [DateTime](./) مشخص شده است. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | نمایش رشته‌ای مشخص‌شدهٔ یک مقدار تاریخ و زمان را به شیء معادل [DateTime](./) تبدیل می‌کند. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | نمایش رشته‌ای مشخص‌شدهٔ یک مقدار تاریخ و زمان را با استفاده از اطلاعات قالب مخصوص فرهنگ، به شیء معادل [DateTime](./) تبدیل می‌کند. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | نمایش رشته‌ای مشخص‌شدهٔ یک مقدار تاریخ و زمان را با استفاده از قالب مشخص‌شده و اطلاعات قالب مخصوص فرهنگ، به شیء معادل [DateTime](./) تبدیل می‌کند. قالب نمایش رشته باید دقیقاً با قالب مشخص‌شده مطابقت داشته باشد. در صورت شکست تبدیل، استثنایی پرتاب می‌شود. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | نمایش رشته‌ای مشخص‌شدهٔ یک مقدار تاریخ و زمان را با استفاده از قالب‌های مشخص‌شده، اطلاعات قالب مخصوص فرهنگ و سبک، به شیء معادل [DateTime](./) تبدیل می‌کند. قالب نمایش رشته باید دقیقاً با یک یا چند قالب مشخص‌شده مطابقت داشته باشد. در صورت شکست تبدیل، استثنایی پرتاب می‌شود. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | یک شیء جدید [DateTime](./) می‌سازد که تعداد تیک‌های مشابه شیء [DateTime](./) مشخص‌شده را نمایان می‌سازد و زمان محلی، زمان UTC یا هیچ‌کدام را بر حسب آرگومان **kind** نشان می‌دهد. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | یک نمونهٔ جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان حاصل از تفریق بازه زمانی مشخص‌شده از مقدار نمایان‌شده توسط شیء فعلی را نشان می‌دهد. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | یک نمونه از کلاس [TimeSpan](../timespan/) را برمی‌گرداند که بازهٔ زمانی بین مقادیر تاریخ و زمان نمایان‌شده توسط شیء فعلی و شیء مشخص‌شده را نشان می‌دهد. |
| **int64_t** [ToBinary](./tobinary/)() const | شیء فعلی را سریال‌سازی می‌کند. |
| **int64_t** [ToFileTime](./tofiletime/)() const | مقداری را برمی‌گرداند که مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را به عنوان زمان فایل (File time) نشان می‌دهد. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را به زمان فایل UTC تبدیل می‌کند. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | یک نمونهٔ جدید از کلاس [DateTime](./) را برمی‌گرداند که مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را به عنوان زمان محلی نشان می‌دهد. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | رشته‌ای شامل نمایش رشته‌ای تاریخ طولانی شیء فعلی را برمی‌گرداند. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | رشته‌ای شامل نمایش رشته‌ای زمان طولانی شیء فعلی را برمی‌گرداند. |
| **double** [ToOADate](./tooadate/)() const | مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را به عنوان تاریخ OLE Automation برمی‌گرداند. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | رشته‌ای شامل نمایش رشته‌ای تاریخ کوتاه شیء فعلی را برمی‌گرداند. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | رشته‌ای شامل نمایش رشته‌ای زمان کوتاه شیء فعلی را برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)() const | نمایش رشته‌ای مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را با استفاده از قواعد قالب‌بندی تعریف‌شده توسط فرهنگ جاری برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | نمایش رشته‌ای مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را با استفاده از قالب مشخص‌شده و قواعد قالب‌بندی تعریف‌شده توسط فرهنگ جاری برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | نمایش رشته‌ای مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را با استفاده از اطلاعات قالب مشخص‌شده برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | نمایش رشته‌ای مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را با استفاده از اطلاعات قالب مشخص‌شده برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | یک نمونهٔ جدید از کلاس [DateTime](./) برمی‌گرداند که مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را به عنوان UTC نشان می‌دهد. |
| time_t [ToUnixTime](./tounixtime/)() const | مقداری را برمی‌گرداند که مقدار تاریخ و زمان نمایان‌شده توسط شیء فعلی را به عنوان زمان یونیکس نشان می‌دهد. برای استفاده داخلی. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | نمایش رشته‌ای مشخص‌شدهٔ یک مقدار تاریخ و زمان را به شیء معادل [DateTime](./) تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | نمایش رشته‌ای مشخص‌شدهٔ یک مقدار تاریخ و زمان را با استفاده از اطلاعات قالب مخصوص فرهنگ و سبک مشخص‌شده، به شیء معادل [DateTime](./) تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | نمایش رشته‌ای مشخص‌شدهٔ یک مقدار تاریخ و زمان را با استفاده از قالب مشخص‌شده، اطلاعات قالب مخصوص فرهنگ و سبک، به شیء معادل [DateTime](./) تبدیل می‌کند. قالب نمایش رشته باید دقیقاً با قالب مشخص‌شده مطابقت داشته باشد. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | نمایش رشته‌ای مشخص‌شدهٔ یک مقدار تاریخ و زمان را با استفاده از قالب‌های مشخص‌شده، اطلاعات قالب مخصوص فرهنگ و سبک، به شیء معادل [DateTime](./) تبدیل می‌کند. قالب نمایش رشته باید دقیقاً با یک یا چند قالب مشخص‌شده مطابقت داشته باشد. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | یک شیء [TypeInfo](../typeinfo/) را برمی‌گرداند که شامل اطلاعاتی دربارهٔ این کلاس است. |

## فیلدها

| فیلد | توضیحات |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | تعداد ۱۰۰ نانوثانیه در بازهٔ زمانی بین کمترین مقدار ممکن و بیشترین مقدار ممکن [DateTime](./). |
| static [MaxValue](./maxvalue/) | یک نمونه از کلاس [DateTime](./) که بیشترین مقدار ممکن تاریخ و زمان را نشان می‌دهد. |
| static constexpr [MinTicks](./minticks/) | حداقل تعداد تیک‌هایی که یک نمونه از کلاس [DateTime](./) می‌تواند نمایند. |
| static [MinValue](./minvalue/) | یک نمونه از کلاس [DateTime](./) که کمترین مقدار ممکن تاریخ و زمان را نشان می‌دهد. |
| static constexpr [TicksPerDay](./ticksperday/) | تعداد تیک‌ها در یک روز. |
| static constexpr [TicksPerHour](./ticksperhour/) | تعداد تیک‌ها در یک ساعت. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | تعداد تیک‌ها در یک میکروثانیه. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | تعداد تیک‌ها در یک میلیثانیه. |
| static constexpr [TicksPerMinute](./ticksperminute/) | تعداد تیک‌ها در یک دقیقه. |
| static constexpr [TicksPerSecond](./tickspersecond/) | تعداد تیک‌ها در یک ثانیه. |
| static [UnixEpoch](./unixepoch/) | یک نمونه از کلاس [DateTime](./) که شروع عصر یونیکس (۱۹۷۰/۰۱/۰۱ ۰۰:۰۰:۰۰) را نشان می‌دهد. |

## توضیحات

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // یک نمونه از کلاس 'DateTime' ایجاد کنید.
  DateTime dateTime{1990, 10, 30};

  // نمونه را در قالب‌های مختلف چاپ کنید.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## مراجع

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)