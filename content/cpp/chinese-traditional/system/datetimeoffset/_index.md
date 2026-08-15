---
title: DateTimeOffset
second_title: Aspose.Slides for C++ API 參考
description: "包含相對於協調世界時的日期與時間。此類別的物件應僅使用 System::MakeObject() 函式分配。絕不可在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別封裝於 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 235
url: /zh-hant/system/datetimeoffset/
---
## DateTimeOffset 類別

包含相對於協調世界時的日期與時間。此類別的物件應僅使用 [System::MakeObject()](../makeobject/) 函式分配。絕不可在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別封裝於 [System::SmartPtr](../smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class DateTimeOffset
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | 將指定的時間間隔加入到 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | 將指定天數加入到 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | 將指定小時數加入到 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | 將指定毫秒數加入到 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | 將指定分鐘數加入到 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | 將指定月數加入到 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | 將指定秒數加入到 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | 將指定 tick 數加入到 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | 將指定年數加入到 [DateTimeOffset](./) 物件。 |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | 比較兩個 [DateTimeOffset](./) 物件。 |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | 比較兩個 [DateTimeOffset](./) 物件。 |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 比較兩個 [DateTimeOffset](./) 物件。 |
| constexpr [DateTimeOffset](./datetimeoffset/)() | 預設建構子。 |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | 建構子。 |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | 建構子。 |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | 建構子。 |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | 建構子。 |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | 建構子。 |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | 建構子。 |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | 檢查兩個 [DateTimeOffset](./) 物件是否表示相同的時間點。 |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | 檢查兩個 [DateTimeOffset](./) 物件是否表示相同的時間點。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 檢查兩個 [DateTimeOffset](./) 物件是否表示相同的時間點。 |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | 檢查兩個 [DateTimeOffset](./) 物件是否表示相同的時間點且具有相同的偏移。 |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 檢查兩個 [DateTimeOffset](./) 物件是否表示相同的時間點且具有相同的偏移。 |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) 檔案時間轉換為帶本地時間偏移的日期和時間。 |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix 時間轉換為 [DateTimeOffset](./) 物件。 |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix 時間轉換為 [DateTimeOffset](./) 物件。 |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | 取得目前物件的日期部分。 |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | 取得 [DateTime](../datetime/) 值。 |
| int [get_Day](./get_day/)() const | 取得目前物件的月份天數。 |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | 取得目前物件的星期幾。 |
| int [get_DayOfYear](./get_dayofyear/)() const | 取得目前物件的年度第幾天。 |
| int [get_Hour](./get_hour/)() const | 取得目前物件的時鐘小時部分。 |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | 取得代表本地日期時間的 [DateTime](../datetime/) 值。 |
| constexpr int [get_Millisecond](./get_millisecond/)() const | 取得目前物件的毫秒部分。 |
| int [get_Minute](./get_minute/)() const | 取得目前物件的分鐘部分。 |
| int [get_Month](./get_month/)() const | 取得目前物件的月份部分。 |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | 取得 [DateTimeOffset](./)，其日期和時間設定為目前本地時間，且偏移設定為本地時間的偏移。 |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | 取得相對於 UTC 的偏移。 |
| constexpr int [get_Second](./get_second/)() const | 取得目前物件的秒數部分。 |
| **int64_t** [get_Ticks](./get_ticks/)() const | 取得目前物件的 tick 數量。 |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | 取得目前物件的當日時間。 |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | 取得代表 UTC 日期時間的 [DateTime](../datetime/) 值。 |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | 取得 [DateTimeOffset](./)，其日期和時間設定為目前 UTC 時間，且偏移為 [TimeSpan::Zero](../timespan/zero/)。 |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | 取得目前物件在 UTC 時間的 tick 數量。 |
| int [get_Year](./get_year/)() const | 取得目前物件的年度部分。 |
| int [GetHashCode](./gethashcode/)() const | 取得目前 [DateTimeOffset](./) 物件的雜湊碼。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | 判斷目前物件與指定的 [DateTimeOffset](./) 物件是否表示不同的日期時間值。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | 傳回一個新的 [DateTimeOffset](./) 類別實例，表示目前物件與指定時間跨度之和的日期時間值。 |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | 傳回一個新的 [DateTimeOffset](./) 類別實例，表示從目前物件所代表的值減去指定時間跨度後的日期時間值。 |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | 傳回一個 [TimeSpan](../timespan/) 類別實例，表示目前與指定物件所代表的日期時間值之間的時間間隔。 |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | 判斷目前物件所代表的日期時間值是否早於指定的 [DateTimeOffset](./) 物件的值。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | 判斷目前物件所代表的日期時間值是否早於或等於指定的 [DateTimeOffset](./) 物件的值。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | 判斷目前物件與指定的 [DateTimeOffset](./) 物件是否表示相同的日期時間值。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | 判斷目前物件所代表的日期時間值是否晚於指定的 [DateTimeOffset](./) 物件的值。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | 判斷目前物件所代表的日期時間值是否晚於或等於指定的 [DateTimeOffset](./) 物件的值。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | 將指定的字串轉換為 [DateTimeOffset](./) 等價物。 |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用指定的格式提供程式和格式樣式，將指定字串轉換為 [DateTimeOffset](./) 物件。 |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用指定的格式、格式提供程式和格式樣式，將指定字串轉換為 [DateTimeOffset](./) 物件。 |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 使用指定的多種格式、格式提供程式和格式樣式，將指定字串轉換為 [DateTimeOffset](./) 物件。 |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | 從目前物件減去指定的時間間隔。 |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | 從目前物件減去指定的 [DateTimeOffset](./) 值。 |
| **int64_t** [ToFileTime](./tofiletime/)() const | 將目前物件轉換為 [Windows](../../system.windows/) 檔案時間。 |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | 將目前物件轉換為代表本地時間的物件。 |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | 以指定的偏移取代目前物件的偏移。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的格式與格式提供程式，將目前物件轉換為字串。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的格式提供程式，將目前物件轉換為字串。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 使用指定的格式，將目前物件轉換為字串。 |
| [String](../string/) [ToString](./tostring/)() const | 將目前物件轉換為字串。 |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | 將目前物件轉換為代表 UTC 時間的物件。 |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | 取得自 Unix 紀元開始以來經過的毫秒數。 |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | 取得自 Unix 紀元開始以來經過的秒數。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | 嘗試將指定的字串轉換為 [DateTimeOffset](./) 物件。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 使用指定的格式提供程式與格式樣式，嘗試將指定的字串轉換為 [DateTimeOffset](./) 物件。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 使用指定的多種格式、格式提供程式與格式樣式，嘗試將指定的字串轉換為 [DateTimeOffset](./) 物件。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 使用指定的格式、格式提供程式與格式樣式，嘗試將指定的字串轉換為 [DateTimeOffset](./) 物件。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 傳回一個代表 [TimeSpan](../timespan/) 結構的 [TypeInfo](../typeinfo/) 物件。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | 取得最大的 tick 偏移。 |
| static [MaxValue](./maxvalue/) | 取得最大的 [DateTimeOffset](./) 值。 |
| static constexpr [MinOffset](./minoffset/) | 取得最小的 tick 偏移。 |
| static [MinValue](./minvalue/) | 取得最早的 [DateTimeOffset](./) 值。 |
| static [UnixEpoch](./unixepoch/) | 取得 Unix 紀元的開始時間。 |

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)