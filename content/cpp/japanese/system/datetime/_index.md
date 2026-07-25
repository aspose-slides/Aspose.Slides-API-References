---
title: DateTime
second_title: Aspose.Slides for C++ API リファレンス
description: "時間軸上の特定の日時値を表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 222
url: /ja/system/datetime/
---
## DateTime クラス

時間軸上の特定の日付と時刻の値を表します。この型はスタックに割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class DateTime
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、指定された時間間隔を現在のオブジェクトが表す日付と時刻の値に加算した結果の日時値を表します。 |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値と指定された日数の合計の日時値を表します。 |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値と指定された時間数の合計の日時値を表します。 |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値と指定されたミリ秒数の合計の日時値を表します。 |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値と指定された分数の合計の日時値を表します。 |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値と指定された月数の合計の日時値を表します。 |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値と指定された秒数の合計の日時値を表します。 |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値と指定された 100 ナノ秒間隔の合計の日時値を表します。 |
| [DateTime](./) [AddYears](./addyears/)(int) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す日時値の年コンポーネントを指定された数だけ増加させた日時値を表します。 |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | 指定された [DateTime](./) クラスのインスタンスが表す 2 つの値を比較し、時間軸上での相対的な位置を示す値を返します。 |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | 現在のオブジェクトが表す日時値と指定された [DateTime](./) クラスのインスタンスが表す日時値の 2 つを比較し、時間軸上での相対的な位置を示す値を返します。 |
| constexpr [DateTime](./datetime/)() | 最小可能な日時値（MinValue）を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(int, int, int) | 特定の年、月、日で指定された日時値を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | 指定されたカレンダーで特定の年、月、日で指定された日時値を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | 特定の年、月、日、時、分、秒で指定された日時値を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | 特定の年、月、日、時、分、秒で指定された日時値を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | 指定されたカレンダーで特定の年、月、日、時、分、秒で指定された日時値を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | 特定の年、月、日、時、分、秒、ミリ秒で指定された日時値を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | 指定されたカレンダーで特定の年、月、日、時、分、秒、ミリ秒で指定された日時値を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | ティック数で指定された日時値を表すインスタンスを構築します。 |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | ティック数で指定された日時値を表すインスタンスを構築します。内部使用向けです。 |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | インスタンスをコピー構築します。 |
| static int [DaysInMonth](./daysinmonth/)(int, int) | 指定された年の指定された月の日数を返します。 |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | 指定された [DateTime](./) クラスのインスタンスが同じ日時値を表すかどうかを判定します。 |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | 指定された [DateTime](./) クラスのインスタンスが現在のオブジェクトと同じ日時値を表すかどうかを判定します。 |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | 指定された符号なし 64 ビット整数から日時値をデシリアライズし、新しい [DateTime](./) クラスのインスタンスにその値を設定します。 |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | 指定されたファイル時間をローカル時間と同じ日時値を表す [DateTime](./) クラスのインスタンスに変換します。 |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | 指定されたファイル時間を UTC 時間と同じ日時値を表す [DateTime](./) クラスのインスタンスに変換します。 |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | 指定された OLE Automation Date と等価な日時値を表す [DateTime](./) クラスのインスタンスを返します。 |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | 指定された Unix 時間値を [DateTime](./) クラスのインスタンスに変換します。内部使用向けです。 |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | 現在のオブジェクトが表す日時のうち、時間部分のすべてのコンポーネントを 0 に設定した日付部分のみを表す [DateTime](./) クラスの新しいインスタンスを返します。 |
| int [get_Day](./get_day/)() const | 現在のオブジェクトが表す月の中での日付（序数）を返します。 |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | 現在のオブジェクトが表す曜日を表す値を返します。 |
| int [get_DayOfYear](./get_dayofyear/)() const | 現在のオブジェクトが表す年の中での日付（序数）を返します。 |
| constexpr int [get_Hour](./get_hour/)() const | 現在のオブジェクトが表す日時の時間コンポーネントを返します。 |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | 現在のオブジェクトが表す日時がローカルか UTC か、またはどちらでもないかを示す値を返します。 |
| constexpr int [get_Millisecond](./get_millisecond/)() const | 現在のオブジェクトが表す日時のミリ秒コンポーネントを返します。 |
| constexpr int [get_Minute](./get_minute/)() const | 現在のオブジェクトが表す日時の分コンポーネントを返します。 |
| int [get_Month](./get_month/)() const | 現在のオブジェクトが表す年の中での月の序数を返します。 |
| static [DateTime](./) [get_Now](./get_now/)() | 現在の時刻をローカル時間として表す [DateTime](./) クラスのインスタンスを返します。 |
| constexpr int [get_Second](./get_second/)() const | 現在のオブジェクトが表す日時の秒コンポーネントを返します。 |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | 現在のオブジェクトが表す日時まで、グレゴリオ暦で 0001 年 1 月 1 日 0:00:00 UTC から経過した 100 ナノ秒間隔の数を返します。 |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | 現在のオブジェクトが表す日の開始時点から現在の日時までの時間間隔を表す値を返します。 |
| static [DateTime](./) [get_Today](./get_today/)() | オブジェクトが表す日時の時間部分をすべて 0 に設定した、現在の日付を表す [DateTime](./) クラスのインスタンスを返します。 |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | 現在の時刻を UTC として表す [DateTime](./) クラスのインスタンスを返します。 |
| int [get_Year](./get_year/)() const | 現在のオブジェクトが表す年を返します。 |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | 日付部分を取得します。内部使用向けです。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | 現在のオブジェクトを標準の日時書式指定子のいずれかでフォーマットした文字列表現の配列を返します。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | 指定された標準の日時書式指定子でフォーマットした現在のオブジェクトの文字列表現の配列を返します。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 標準の日時書式指定子のいずれかと指定された書式プロバイダーでフォーマットした現在のオブジェクトの文字列表現の配列を返します。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 指定された標準の日時書式指定子と書式プロバイダーでフォーマットした現在のオブジェクトの文字列表現の配列を返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | 現在のオブジェクトが表す日時が現在のタイムゾーンの夏時間範囲に含まれるかどうかを判定します。 |
| static **bool** [IsLeapYear](./isleapyear/)(int) | 指定された年がうるう年かどうかを判定します。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | 現在のオブジェクトと指定された [DateTime](./) オブジェクトが異なる日時値を表すかどうかを判定します。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値と指定された時間間隔の合計の日時値を表します。 |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | 現在のオブジェクトを、現在のオブジェクトが表す値と指定された時間間隔の合計の日時値に設定します。 |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | [DateTime](./) クラスの新しいインスタンスを返します。これは、現在のオブジェクトが表す値から指定された時間間隔を減算した結果の日時値を表します。 |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | [TimeSpan](../timespan/) クラスのインスタンスを返します。これは、現在のオブジェクトと指定されたオブジェクトが表す日時値間の時間間隔を表します。 |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | 現在のオブジェクトを、現在のオブジェクトが表す日時値から指定された時間間隔を減算した結果の日時値に設定します。 |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | 現在のオブジェクトが指定された [DateTime](./) オブジェクトが表す日時値よりも早いかどうかを判定します。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | 現在のオブジェクトが指定された [DateTime](./) オブジェクトが表す日時値よりも早いか、または同じかどうかを判定します。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | 指定された [DateTime](./) インスタンスが表す値を現在のオブジェクトに代入します。 |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | 現在のオブジェクトと指定された [DateTime](./) オブジェクトが同じ日時値を表すかどうかを判定します。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | 現在のオブジェクトが、指定された[DateTime](./)オブジェクトが表す値より後の日時値を表しているかどうかを判断します。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | 現在のオブジェクトが、指定された[DateTime](./)オブジェクトが表す値と同じかそれより後の日時値を表しているかどうかを判断します。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | 指定された日付時刻値の文字列表現を、同等の[DateTime](./)オブジェクトに変換します。 |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | カルチャ固有の書式情報を使用して、指定された日付時刻値の文字列表現を同等の[DateTime](./)オブジェクトに変換します。 |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 指定された書式とカルチャ固有の書式情報を使用して、指定された日付時刻値の文字列表現を同等の[DateTime](./)オブジェクトに変換します。文字列の書式は指定された書式と完全に一致している必要があります。変換に失敗した場合は例外をスローします。 |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 指定された書式、カルチャ固有の書式情報、およびスタイルを使用して、指定された日付時刻値の文字列表現を同等の[DateTime](./)オブジェクトに変換します。文字列の書式は指定された書式のいずれかと完全に一致している必要があります。変換に失敗した場合は例外をスローします。 |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | 引数**kind**で指定されたローカル時間、UTC 時間、またはそれ以外を表すように、指定された[DateTime](./)オブジェクトと同じティック数を持つ新しい[DateTime](./)オブジェクトを構築します。 |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | 現在のオブジェクトが表す値から指定された時間間隔を減算した結果としての日付時刻値を表す[DateTime](./)クラスの新しいインスタンスを返します。 |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | 現在のオブジェクトと指定されたオブジェクトが表す日付時刻値の間の時間間隔を表す[TimeSpan](../timespan/)クラスのインスタンスを返します。 |
| **int64_t** [ToBinary](./tobinary/)() const | 現在のオブジェクトをシリアライズします。 |
| **int64_t** [ToFileTime](./tofiletime/)() const | 現在のオブジェクトが表す日付時刻値をファイル時間として表す値を返します。 |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | 現在のオブジェクトが表す日付時刻値を UTC のファイル時間に変換します。 |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | [DateTime](./)クラスの新しいインスタンスを返します。このインスタンスは現在のオブジェクトが表す日付時刻値をローカル時間として表します。 |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | 現在のオブジェクトの長い日付文字列表現を含む文字列を返します。 |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | 現在のオブジェクトの長い時刻文字列表現を含む文字列を返します。 |
| **double** [ToOADate](./tooadate/)() const | 現在のオブジェクトが表す日付時刻値を OLE Automation Date として返します。 |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | 現在のオブジェクトの短い日付文字列表現を含む文字列を返します。 |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | 現在のオブジェクトの短い時刻文字列表現を含む文字列を返します。 |
| [String](../string/) [ToString](./tostring/)() const | 現在のカルチャで定義された書式規則を使用して、現在のオブジェクトが表す日付時刻値の文字列表現を返します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 現在のカルチャで定義された書式規則と指定された書式を使用して、現在のオブジェクトが表す日付時刻値の文字列表現を返します。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 指定された書式情報を使用して、現在のオブジェクトが表す日付時刻値の文字列表現を返します。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 指定された書式情報を使用して、現在のオブジェクトが表す日付時刻値の文字列表現を返します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | [DateTime](./)クラスの新しいインスタンスを返します。このインスタンスは現在のオブジェクトが表す日付時刻値を UTC として表します。 |
| time_t [ToUnixTime](./tounixtime/)() const | 現在のオブジェクトが表す日付時刻値を Unix 時間として表す値を返します。（内部使用のためのものです。） |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | 指定された日付時刻値の文字列表現を、同等の[DateTime](./)オブジェクトに変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 指定されたカルチャ固有の書式情報とスタイルを使用して、指定された日付時刻値の文字列表現を同等の[DateTime](./)オブジェクトに変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 指定された書式、カルチャ固有の書式情報、スタイルを使用して、指定された日付時刻値の文字列表現を同等の[DateTime](./)オブジェクトに変換します。文字列の書式は指定された書式と完全に一致している必要があります。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 指定された書式、カルチャ固有の書式情報、スタイルを使用して、指定された日付時刻値の文字列表現を同等の[DateTime](./)オブジェクトに変換します。文字列の書式は指定された書式のいずれかと完全に一致している必要があります。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | このクラスに関する情報を含む[TypeInfo](../typeinfo/)オブジェクトを返します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | 最小可能および最大可能[DateTime](./)値の間の時間間隔における100ナノ秒単位の数。 |
| static [MaxValue](./maxvalue/) | [DateTime](./)クラスのインスタンスで、最大可能な日付時刻値を表します。 |
| static constexpr [MinTicks](./minticks/) | [DateTime](./)クラスのインスタンスが表すことのできる最小のティック数です。 |
| static [MinValue](./minvalue/) | [DateTime](./)クラスのインスタンスで、最小可能な日付時刻値を表します。 |
| static constexpr [TicksPerDay](./ticksperday/) | 1日のティック数。 |
| static constexpr [TicksPerHour](./ticksperhour/) | 1時間のティック数。 |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | 1マイクロ秒のティック数。 |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | 1ミリ秒のティック数。 |
| static constexpr [TicksPerMinute](./ticksperminute/) | 1分のティック数。 |
| static constexpr [TicksPerSecond](./tickspersecond/) | 1秒のティック数。 |
| static [UnixEpoch](./unixepoch/) | [DateTime](./)クラスのインスタンスで、Unix エポック開始（1970-01-01 00:00:00）を表します。 |

## 備考

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // 'DateTime' クラスのインスタンスを作成します.
  DateTime dateTime{1990, 10, 30};

  // インスタンスを複数の形式で出力します.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
このコード例は次の出力を生成します:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)