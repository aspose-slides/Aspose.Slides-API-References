---
title: DateTimeOffset
second_title: مرجع API Aspose.Slides برای C++
description: "این کلاس تاریخ و زمان روز را نسبت به زمان هماهنگ جهانی (UTC) در بر دارد. اشیاء این کلاس باید تنها با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اطمینان می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس کردن آن به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 235
url: /fa/system/datetimeoffset/
---
## DateTimeOffset کلاس

حاوی تاریخ و زمان روز نسبت به زمان هماهنگ جهانی است. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اطمینان می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../smartptr/) بپیچید و از این اشاره‌گر برای عبور آن به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class DateTimeOffset
```

## متدها

| متد | توضیح |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | یک بازه زمان مشخص را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | یک تعداد مشخص از روزها را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | یک تعداد مشخصی از ساعت‌ها را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | یک تعداد مشخصی از میلی‌ثانیه‌ها را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | یک تعداد مشخصی از دقیقه‌ها را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | یک تعداد مشخصی از ماه‌ها را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | یک تعداد مشخصی از ثانیه‌ها را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | یک تعداد مشخصی از تیک‌ها را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | یک تعداد مشخصی از سال‌ها را به شیء [DateTimeOffset](./) اضافه می‌کند. |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | دو شیء [DateTimeOffset](./) را مقایسه می‌کند. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | دو شیء [DateTimeOffset](./) را مقایسه می‌کند. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | دو شیء [DateTimeOffset](./) را مقایسه می‌کند. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | سازنده پیش‌فرض. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | سازنده. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | سازنده. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | سازنده. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | سازنده. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | سازنده. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | سازنده. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | بررسی می‌کند که آیا دو شیء [DateTimeOffset](./) همان نقطه زمانی را نشان می‌دهند یا خیر. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | بررسی می‌کند که آیا دو شیء [DateTimeOffset](./) همان نقطه زمانی را نشان می‌دهند یا خیر. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | بررسی می‌کند که آیا دو شیء [DateTimeOffset](./) همان نقطه زمانی را نشان می‌دهند یا خیر. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | بررسی می‌کند که آیا دو شیء [DateTimeOffset](./) همان نقطه زمانی را نشان می‌دهند و جابجایی یکسانی دارند یا خیر. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | بررسی می‌کند که آیا دو شیء [DateTimeOffset](./) همان نقطه زمانی را نشان می‌دهند و جابجایی یکسانی دارند یا خیر. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) زمان فایل به تاریخ و زمان با جابجایی زمان محلی. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) زمان یونیکس به شیء [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) زمان یونیکس به شیء [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | جزء تاریخ شیء فعلی را دریافت می‌کند. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | مقدار [DateTime](../datetime/) را دریافت می‌کند. |
| int [get_Day](./get_day/)() const | روز ماه شیء فعلی را دریافت می‌کند. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | روز هفته شیء فعلی را دریافت می‌کند. |
| int [get_DayOfYear](./get_dayofyear/)() const | روز سال شیء فعلی را دریافت می‌کند. |
| int [get_Hour](./get_hour/)() const | جزء ساعت شیء فعلی را دریافت می‌کند. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | مقدار [DateTime](../datetime/) که تاریخ و زمان محلی را نمایندگی می‌کند، دریافت می‌کند. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | جزء میلی‌ثانیه شیء فعلی را دریافت می‌کند. |
| int [get_Minute](./get_minute/)() const | جزء دقیقه شیء فعلی را دریافت می‌کند. |
| int [get_Month](./get_month/)() const | جزء ماه شیء فعلی را دریافت می‌کند. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | یک [DateTimeOffset](./) دریافت می‌کند که تاریخ و زمان آن برابر با زمان محل فعلی تنظیم شده و جابجایی آن برابر با جابجایی زمان محلی است. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | جابجایی نسبت به UTC را دریافت می‌کند. |
| constexpr int [get_Second](./get_second/)() const | جزء ثانیه شیء فعلی را دریافت می‌کند. |
| **int64_t** [get_Ticks](./get_ticks/)() const | تعداد تیک‌های شیء فعلی را دریافت می‌کند. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | زمان روز شیء فعلی را دریافت می‌کند. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | مقدار [DateTime](../datetime/) که تاریخ و زمان UTC را نمایش می‌دهد، دریافت می‌کند. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | یک [DateTimeOffset](./) دریافت می‌کند که تاریخ و زمان آن برابر با زمان UTC فعلی تنظیم شده و جابجایی آن [TimeSpan::Zero](../timespan/zero/) است. |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | تعداد تیک‌های شیء فعلی را در زمان UTC دریافت می‌کند. |
| int [get_Year](./get_year/)() const | جزء سال شیء فعلی را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const | کد هش برای شیء [DateTimeOffset](./) فعلی را دریافت می‌کند. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | تعیین می‌کند که آیا شیء فعلی و شیء [DateTimeOffset](./) مشخص شده مقادیر تاریخ و زمان متفاوتی دارند یا خیر. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | یک نمونه جدید از کلاس [DateTimeOffset](./) برمی‌گرداند که مقدار تاریخ و زمان را که مجموع مقدار نمایان‌گر شیء فعلی و بازه زمانی مشخص‌شده است، نمایش می‌دهد. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | یک نمونه جدید از کلاس [DateTimeOffset](./) برمی‌گرداند که مقدار تاریخ و زمان را که نتیجهٔ تفریق بازه زمانی مشخص‌شده از مقدار نمایان‌گر شیء فعلی است، نمایش می‌دهد. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | یک نمونه از کلاس [TimeSpan](../timespan/) برمی‌گرداند که بازه زمانی بین مقادیر تاریخ و زمان نمایان‌گر شیء فعلی و شیء مشخص‌شده را نشان می‌دهد. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | تعیین می‌کند که آیا شیء فعلی نمایانگر مقدار تاریخ و زمان قبلی نسبت به مقدار نمایان‌گر شیء [DateTimeOffset](./) مشخص شده است یا خیر. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | تعیین می‌کند که آیا شیء فعلی نمایانگر مقدار تاریخ و زمان قبلی یا مساوی با مقدار نمایان‌گر شیء [DateTimeOffset](./) مشخص شده است یا خیر. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | تعیین می‌کند که آیا شیء فعلی و شیء [DateTimeOffset](./) مشخص شده همان مقدار تاریخ و زمان را نمایندگی می‌کنند یا خیر. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | تعیین می‌کند که آیا شیء فعلی نمایانگر مقدار تاریخ و زمان بعدی نسبت به مقدار نمایان‌گر شیء [DateTimeOffset](./) مشخص شده است یا خیر. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | تعیین می‌کند که آیا شیء فعلی نمایانگر مقدار تاریخ و زمان بعدی یا مساوی با مقدار نمایان‌گر شیء [DateTimeOffset](./) مشخص شده است یا خیر. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | رشتهٔ مشخص‌شده را به معادل [DateTimeOffset](./) تبدیل می‌کند. |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](./) تبدیل می‌کند با استفاده از ارائه‌دهندهٔ فرمت و سبک قالب‌بندی مشخص‌شده. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](./) تبدیل می‌کند با استفاده از فرمت، ارائه‌دهندهٔ فرمت و سبک قالب‌بندی مشخص‌شده. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](./) تبدیل می‌کند با استفاده از فرمت‌های مشخص‌شده، ارائه‌دهندهٔ فرمت و سبک قالب‌بندی. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | یک بازه زمان مشخص را از شیء فعلی کم می‌کند. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | یک مقدار [DateTimeOffset](./) مشخص را از شیء فعلی کم می‌کند. |
| **int64_t** [ToFileTime](./tofiletime/)() const | شیء فعلی را به زمان فایل [Windows](../../system.windows/) تبدیل می‌کند. |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | شیء فعلی را به شیئی که زمان محلی را نشان می‌دهد تبدیل می‌کند. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | جابجایی شیء فعلی را با جابجایی مشخص‌شده جایگزین می‌کند. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | شیء فعلی را به رشته تبدیل می‌کند با استفاده از فرمت و ارائه‌دهندهٔ فرمت مشخص‌شده. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | شیء فعلی را به رشته تبدیل می‌کند با استفاده از ارائه‌دهندهٔ فرمت مشخص‌شده. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | شیء فعلی را به رشته تبدیل می‌کند با استفاده از فرمت مشخص‌شده. |
| [String](../string/) [ToString](./tostring/)() const | شیء فعلی را به رشته تبدیل می‌کند. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | شیء فعلی را به شیئی که زمان UTC را نشان می‌دهد تبدیل می‌کند. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | میلی‌ثانیه‌های گذشته از ابتدا دوره یونیکس را دریافت می‌کند. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | ثانیه‌های گذشته از ابتدا دوره یونیکس را دریافت می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | سعی می‌کند رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](./) تبدیل کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | سعی می‌کند رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](./) تبدیل کند با استفاده از ارائه‌دهندهٔ فرمت و سبک قالب‌بندی مشخص‌شده. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | سعی می‌کند رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](./) تبدیل کند با استفاده از فرمت‌های مشخص‌شده، ارائه‌دهندهٔ فرمت و سبک قالب‌بندی. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | سعی می‌کند رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](./) تبدیل کند با استفاده از فرمت، ارائه‌دهندهٔ فرمت و سبک قالب‌بندی مشخص‌شده. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | یک شیء [TypeInfo](../typeinfo/) که ساختار [TimeSpan](../timespan/) را نمایندگی می‌کند برمی‌گرداند. |
## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | حداقل جابجایی بر حسب تیک‌ها را دریافت می‌کند. |
| static [MaxValue](./maxvalue/) | بزرگ‌ترین مقدار [DateTimeOffset](./) را دریافت می‌کند. |
| static constexpr [MinOffset](./minoffset/) | حداقل جابجایی بر حسب تیک‌ها را دریافت می‌کند. |
| static [MinValue](./minvalue/) | اولین مقدار [DateTimeOffset](./) را دریافت می‌کند. |
| static [UnixEpoch](./unixepoch/) | شروع دورهٔ یونیکس را دریافت می‌کند. |
## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)