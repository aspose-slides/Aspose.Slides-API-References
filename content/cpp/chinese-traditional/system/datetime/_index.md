---
title: DateTime
second_title: Aspose.Slides for C++ API 參考手冊
description: "代表時間連續體上特定的日期和時間值。此類型應在堆疊上分配，並以值或引用方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 222
url: /zh-hant/system/datetime/
---
## DateTime 類別

表示時間連續體上特定的日期和時間值。此類型應該分配在堆疊上，並以值或引用傳遞給函式。永遠不要使用 [System::SmartPtr](../smartptr/) 類別 來管理此類型的物件。

```cpp
class DateTime
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | 傳回一個新的 [DateTime](./) 類別實例，該實例表示將指定的時間跨度加入目前物件所代表的日期和時間值後的結果。 |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的值與指定天數的總和所形成的日期和時間值。 |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的值與指定小時數的總和所形成的日期和時間值。 |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的值與指定毫秒數的總和所形成的日期和時間值。 |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的值與指定分鐘數的總和所形成的日期和時間值。 |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的值與指定月數的總和所形成的日期和時間值。 |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的值與指定秒數的總和所形成的日期和時間值。 |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的值與指定的 100 納秒間隔數的總和所形成的日期和時間值。 |
| [DateTime](./) [AddYears](./addyears/)(int) const | 傳回一個新的 [DateTime](./) 類別實例，表示與目前物件相同的日期和時間值，但年份元件增加了指定的數量。 |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | 比較由指定的 [DateTime](./) 類別實例所代表的兩個值，並傳回指示這些值在時間線上相對位置的值。 |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | 比較目前物件與指定的 [DateTime](./) 類別實例所代表的兩個日期和時間值，並傳回指示這些值在時間線上相對位置的值。 |
| constexpr [DateTime](./datetime/)() | 建構一個實例，該實例表示最小可能的日期和時間值，即 MinValue。 |
|  [DateTime](./datetime/)(int, int, int) | 建構一個實例，該實例表示以特定年、月、日指定的日期和時間值。 |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | 建構一個實例，該實例表示在指定曆法中以特定年、月、日指定的日期和時間值。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | 建構一個實例，該實例表示以特定年、月、日、時、分、秒指定的日期和時間值。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | 建構一個實例，該實例表示以特定年、月、日、時、分、秒指定的日期和時間值。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | 建構一個實例，該實例表示在指定曆法中以特定年、月、日、時、分、秒指定的日期和時間值。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | 建構一個實例，該實例表示以特定年、月、日、時、分、秒與毫秒指定的日期和時間值。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | 建構一個實例，該實例表示在指定曆法中以特定年、月、日、時、分、秒與毫秒指定的日期和時間值。 |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | 建構一個實例，該實例表示以指定的滴答數表示的日期和時間值。 |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | 建構一個實例，該實例表示以指定的滴答數表示的日期和時間值。供內部使用。 |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | 以複製方式建構實例。 |
| static int [DaysInMonth](./daysinmonth/)(int, int) | 傳回指定年份中指定月份的天數。 |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | 判斷指定的 [DateTime](./) 類別實例是否代表相同的日期和時間值。 |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | 判斷指定的 [DateTime](./) 類別實例是否與目前物件代表相同的日期和時間值。 |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | 從指定的無號 64 位元整數反序列化日期時間值，並將新建的 [DateTime](./) 類別實例設定為該值。 |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | 將指定的檔案時間轉換為 [DateTime](./) 類別實例，該實例表示與本機時間相同的日期和時間值。 |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | 將指定的檔案時間轉換為 [DateTime](./) 類別實例，該實例表示與 UTC 時間相同的日期和時間值。 |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | 傳回一個 [DateTime](./) 類別實例，該實例表示等同於指定 OLE Automation 日期的日期和時間值。 |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | 將指定的 Unix 時間值轉換為 [DateTime](./) 類別實例。僅供內部使用。 |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | 傳回一個新的 [DateTime](./) 類別實例，該實例表示目前物件所代表的日期時間的日期部分，且時間部分的每個元件均設為 0。 |
| int [get_Day](./get_day/)() const | 傳回目前物件所代表的月份中日期的序號。 |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | 傳回目前物件所代表的星期幾的值。 |
| int [get_DayOfYear](./get_dayofyear/)() const | 傳回目前物件所代表的年份中日期的序號。 |
| constexpr int [get_Hour](./get_hour/)() const | 傳回目前物件所代表的日期時間值的時元件。 |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | 傳回一個值，表示目前物件所代表的日期時間是本機時間、UTC 時間或兩者皆非。 |
| constexpr int [get_Millisecond](./get_millisecond/)() const | 傳回目前物件所代表的日期時間值的毫秒元件。 |
| constexpr int [get_Minute](./get_minute/)() const | 傳回目前物件所代表的日期時間值的分鐘元件。 |
| int [get_Month](./get_month/)() const | 傳回目前物件所代表的年份中月份的序號。 |
| static [DateTime](./) [get_Now](./get_now/)() | 傳回一個 [DateTime](./) 類別實例，該實例表示以本機時間表示的當前時間。 |
| constexpr int [get_Second](./get_second/)() const | 傳回目前物件所代表的日期時間值的秒元件。 |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | 傳回自公曆 0001 年 1 月 1 日 0:00:00 UTC 起至目前物件所代表的日期時間所經過的 100 納秒間隔數。 |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | 傳回一個值，表示從目前物件所代表的當日開始到目前物件所代表的日期時間值的時間間隔。 |
| static [DateTime](./) [get_Today](./get_today/)() | 傳回一個 [DateTime](./) 類別實例，該實例表示當前日期，且該物件所代表的時間部分的每個元件均設為 0。 |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | 傳回一個 [DateTime](./) 類別實例，該實例表示以 UTC 表示的當前時間。 |
| int [get_Year](./get_year/)() const | 傳回目前物件所代表的年份。 |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | 取得日期部分。僅供內部使用。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | 傳回字串陣列，每個元素都是以標準日期和時間格式說明字元之一格式化目前物件的字串表示。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | 傳回字串陣列，每個元素都是使用指定的標準日期和時間格式說明字元格式化目前物件的字串表示。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 傳回字串陣列，每個元素都是使用標準日期和時間格式說明字元之一以及指定的格式提供者格式化目前物件的字串表示。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 傳回字串陣列，每個元素都是使用指定的標準日期和時間格式說明字元及格式提供者格式化目前物件的字串表示。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | 判斷目前物件所代表的日期時間值是否位於目前時區的夏令時間範圍內。 |
| static **bool** [IsLeapYear](./isleapyear/)(int) | 判斷指定的年份是否為閏年。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | 判斷目前物件與指定的 [DateTime](./) 物件是否代表不同的日期和時間值。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | 傳回一個新的 [DateTime](./) 類別實例，該實例表示將指定的時間跨度加入目前物件所代表的值後的日期和時間值。 |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | 將目前物件設定為將指定的時間跨度加入目前物件所代表的值後的日期和時間值。 |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | 傳回一個新的 [DateTime](./) 類別實例，該實例表示從目前物件所代表的值減去指定時間跨度後的日期和時間值。 |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | 傳回一個 [TimeSpan](../timespan/) 類別實例，該實例表示目前物件與指定物件所代表的日期時間值之間的時間間隔。 |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | 將目前物件設定為從目前物件所代表的日期時間值減去指定時間跨度後的日期時間值。 |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | 判斷目前物件所代表的日期時間值是否早於指定的 [DateTime](./) 物件所代表的值。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | 判斷目前物件所代表的日期時間值是否早於或等於指定的 [DateTime](./) 物件所代表的值。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | 將指定的 [DateTime](./) 實例所代表的值指派給目前物件。 |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | 判斷目前物件與指定的 [DateTime](./) 物件是否代表相同的日期和時間值。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | 判斷目前物件所表示的日期和時間值是否晚於指定的 [DateTime](./) 物件所表示的值。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | 判斷目前物件所表示的日期和時間值是否晚於或等於指定的 [DateTime](./) 物件所表示的值。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | 將指定的日期和時間值的字串表示法轉換為等效的 [DateTime](./) 物件。 |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用特定文化的格式資訊，將指定的日期和時間值的字串表示法轉換為等效的 [DateTime](./) 物件。 |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用指定的格式與特定文化的格式資訊，將指定的日期和時間值的字串表示法轉換為等效的 [DateTime](./) 物件。字串表示法的格式必須完全符合指定的格式。若轉換失敗，將拋出例外。 |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用指定的格式、特定文化的格式資訊與樣式，將指定的日期和時間值的字串表示法轉換為等效的 [DateTime](./) 物件。字串表示法的格式必須完全符合一個或多個指定的格式。若轉換失敗，將拋出例外。 |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | 建立一個新的 [DateTime](./) 物件，其 tick 數與指定的 [DateTime](./) 物件相同，並根據參數 **kind** 指定為本地時間、UTC 時間或皆非。 |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | 傳回一個新的 [DateTime](./) 類別實例，表示從目前物件所表示的值減去指定時間跨度後的日期和時間值。 |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | 傳回一個 [TimeSpan](../timespan/) 類別的實例，表示目前物件與指定物件所表示的日期和時間值之間的時間間隔。 |
| **int64_t** [ToBinary](./tobinary/)() const | 序列化目前物件。 |
| **int64_t** [ToFileTime](./tofiletime/)() const | 傳回一個值，以檔案時間 (File time) 形式表示目前物件所代表的日期和時間值。 |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | 將目前物件所代表的日期和時間值轉換為 UTC 檔案時間 (File time)。 |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的本地時間日期和時間值。 |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | 傳回一個字串，包含目前物件的長日期字串表示。 |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | 傳回一個字串，包含目前物件的長時間字串表示。 |
| **double** [ToOADate](./tooadate/)() const | 傳回目前物件所代表的日期和時間值，以 OLE Automation 日期表示。 |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | 傳回一個字串，包含目前物件的短日期字串表示。 |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | 傳回一個字串，包含目前物件的短時間字串表示。 |
| [String](../string/) [ToString](./tostring/)() const | 傳回目前物件所代表的日期和時間值的字串表示，使用目前文化定義的格式慣例。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 使用指定的格式與目前文化定義的格式慣例，傳回目前物件所代表的日期和時間值的字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的格式資訊，傳回目前物件所代表的日期和時間值的字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的格式資訊，傳回目前物件所代表的日期和時間值的字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | 傳回一個新的 [DateTime](./) 類別實例，表示目前物件所代表的 UTC 日期和時間值。 |
| time_t [ToUnixTime](./tounixtime/)() const | 傳回一個值，以 Unix 時間形式表示目前物件所代表的日期和時間值。僅供內部使用。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | 將指定的日期和時間值的字串表示法轉換為等效的 [DateTime](./) 物件。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 將指定的日期和時間值的字串表示法轉換為等效的 [DateTime](./) 物件，使用指定的特定文化格式資訊與樣式。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 使用指定的格式、特定文化的格式資訊與樣式，將指定的日期和時間值的字串表示法轉換為等效的 [DateTime](./) 物件。字串表示法的格式必須完全符合指定的格式。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 使用指定的格式、特定文化的格式資訊與樣式，將指定的日期和時間值的字串表示法轉換為等效的 [DateTime](./) 物件。字串表示法的格式必須完全符合一個或多個指定的格式。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 傳回一個 [TypeInfo](../typeinfo/) 物件，包含有關此類別的資訊。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | 在最小可能與最大可能的 [DateTime](./) 值之間的時間間隔中包含的 100 奈秒數量。 |
| static [MaxValue](./maxvalue/) | 一個 [DateTime](./) 類別的實例，表示最大的可能日期和時間值。 |
| static constexpr [MinTicks](./minticks/) | [DateTime](./) 類別實例可以表示的最小 tick 數量。 |
| static [MinValue](./minvalue/) | 一個 [DateTime](./) 類別的實例，表示最小可能的日期和時間值。 |
| static constexpr [TicksPerDay](./ticksperday/) | 一天中的 tick 數量。 |
| static constexpr [TicksPerHour](./ticksperhour/) | 一小時中的 tick 數量。 |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | 一微秒中的 tick 數量。 |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | 一毫秒中的 tick 數量。 |
| static constexpr [TicksPerMinute](./ticksperminute/) | 一分鐘中的 tick 數量。 |
| static constexpr [TicksPerSecond](./tickspersecond/) | 一秒鐘中的 tick 數量。 |
| static [UnixEpoch](./unixepoch/) | 一個 [DateTime](./) 類別的實例，表示 Unix 紀元開始 (1970-01-01 00:00:00)。 |

## 備註



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // 建立 'DateTime' 類別實例。
  DateTime dateTime{1990, 10, 30};

  // 以多種格式列印該實例。
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
此程式碼範例產生以下輸出：
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)