---
title: DateTimeOffset
second_title: Aspose.Slides for C++ API リファレンス
description: "協定世界時（UTC）に対する日付と時刻を保持します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを引数として関数に渡すようにしてください。"
type: docs
weight: 235
url: /ja/system/datetimeoffset/
---
## DateTimeOffset クラス

Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeOffset
```

## メソッド

| Method | Description |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | 指定された時間間隔を [DateTimeOffset](./) オブジェクトに加えます。 |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | 指定された日数を [DateTimeOffset](./) オブジェクトに加えます。 |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | 指定された時間数（時間）を [DateTimeOffset](./) オブジェクトに加えます。 |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | 指定されたミリ秒数を [DateTimeOffset](./) オブジェクトに加えます。 |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | 指定された分数を [DateTimeOffset](./) オブジェクトに加えます。 |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | 指定された月数を [DateTimeOffset](./) オブジェクトに加えます。 |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | 指定された秒数を [DateTimeOffset](./) オブジェクトに加えます。 |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | 指定されたティック数を [DateTimeOffset](./) オブジェクトに加えます。 |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | 指定された年数を [DateTimeOffset](./) オブジェクトに加えます。 |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | 二つの [DateTimeOffset](./) オブジェクトを比較します。 |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | 二つの [DateTimeOffset](./) オブジェクトを比較します。 |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 二つの [DateTimeOffset](./) オブジェクトを比較します。 |
| constexpr [DateTimeOffset](./datetimeoffset/)() | デフォルトコンストラクタです。 |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | コンストラクタです。 |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | コンストラクタです。 |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | コンストラクタです。 |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | コンストラクタです。 |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | コンストラクタです。 |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | コンストラクタです。 |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | 二つの [DateTimeOffset](./) オブジェクトが同じ時点を表すかどうかをチェックします。 |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | 二つの [DateTimeOffset](./) オブジェクトが同じ時点を表すかどうかをチェックします。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 二つの [DateTimeOffset](./) オブジェクトが同じ時点を表すかどうかをチェックします。 |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | 二つの [DateTimeOffset](./) オブジェクトが同じ時点で、同じオフセットを持つかどうかをチェックします。 |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 二つの [DateTimeOffset](./) オブジェクトが同じ時点で、同じオフセットを持つかどうかをチェックします。 |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) ファイル時刻をローカル時間オフセット付きの日付と時刻に変換します。 |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix 時間を [DateTimeOffset](./) オブジェクトに変換します。 |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix 時間を [DateTimeOffset](./) オブジェクトに変換します。 |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | 現在のオブジェクトの日付コンポーネントを取得します。 |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | [DateTime](../datetime/) の値を取得します。 |
| int [get_Day](./get_day/)() const | 現在のオブジェクトの月の日を取得します。 |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | 現在のオブジェクトの曜日を取得します。 |
| int [get_DayOfYear](./get_dayofyear/)() const | 現在のオブジェクトの年内の日を取得します。 |
| int [get_Hour](./get_hour/)() const | 現在のオブジェクトの時間コンポーネントを取得します。 |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | [DateTime](../datetime/) の値（ローカルの日付と時刻を表す）を取得します。 |
| constexpr int [get_Millisecond](./get_millisecond/)() const | 現在のオブジェクトのミリ秒コンポーネントを取得します。 |
| int [get_Minute](./get_minute/)() const | 現在のオブジェクトの分コンポーネントを取得します。 |
| int [get_Month](./get_month/)() const | 現在のオブジェクトの月コンポーネントを取得します。 |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | 現在のローカル時間に設定された日付と時刻、そしてローカル時間のオフセットが設定された [DateTimeOffset](./) を取得します。 |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | UTC からのオフセットを取得します。 |
| constexpr int [get_Second](./get_second/)() const | 現在のオブジェクトの秒コンポーネントを取得します。 |
| **int64_t** [get_Ticks](./get_ticks/)() const | 現在のオブジェクトのティック数を取得します。 |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | 現在のオブジェクトの時刻（time of day）を取得します。 |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | [DateTime](../datetime/) の値（UTC の日付と時刻を表す）を取得します。 |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | 現在の UTC 時間に設定された日付と時刻、そしてオフセットが [TimeSpan::Zero](../timespan/zero/) の [DateTimeOffset](./) を取得します。 |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | UTC 時間での現在のオブジェクトのティック数を取得します。 |
| int [get_Year](./get_year/)() const | 現在のオブジェクトの年コンポーネントを取得します。 |
| int [GetHashCode](./gethashcode/)() const | 現在の [DateTimeOffset](./) オブジェクトのハッシュコードを取得します。 |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | 現在のオブジェクトと指定された [DateTimeOffset](./) オブジェクトが異なる日付と時刻の値を表すかどうかを判断します。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | 現在のオブジェクトが表す日時と指定された時間間隔の合計を表す [DateTimeOffset](./) クラスの新しいインスタンスを返します。 |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | 現在のオブジェクトが表す日時から指定された時間間隔を減算した結果を表す [DateTimeOffset](./) クラスの新しいインスタンスを返します。 |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | 現在および指定されたオブジェクトが表す日時の間の時間間隔を表す [TimeSpan](../timespan/) クラスのインスタンスを返します。 |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | 現在のオブジェクトが指定された [DateTimeOffset](./) オブジェクトが表す日時よりも早いかどうかを判断します。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | 現在のオブジェクトが指定された [DateTimeOffset](./) オブジェクトが表す日時と同じかそれよりも早いかを判断します。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | 現在のオブジェクトと指定された [DateTimeOffset](./) オブジェクトが同じ日時を表すかどうかを判断します。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | 現在のオブジェクトが指定された [DateTimeOffset](./) オブジェクトが表す日時よりも遅いかどうかを判断します。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | 現在のオブジェクトが指定された [DateTimeOffset](./) オブジェクトが表す日時と同じかそれよりも遅いかを判断します。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列を [DateTimeOffset](./) に変換します。 |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 指定された文字列を、指定されたフォーマットプロバイダーとフォーマットスタイルを使用して [DateTimeOffset](./) オブジェクトに変換します。 |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 指定された文字列を、指定されたフォーマット、フォーマットプロバイダー、フォーマットスタイルを使用して [DateTimeOffset](./) オブジェクトに変換します。 |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 指定された文字列を、指定されたフォーマット群、フォーマットプロバイダー、フォーマットスタイルを使用して [DateTimeOffset](./) オブジェクトに変換します。 |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | 現在のオブジェクトから指定された時間間隔を減算します。 |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | 現在のオブジェクトから指定された [DateTimeOffset](./) の値を減算します。 |
| **int64_t** [ToFileTime](./tofiletime/)() const | 現在のオブジェクトを [Windows](../../system.windows/) ファイル時刻に変換します。 |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | 現在のオブジェクトをローカル時間を表すオブジェクトに変換します。 |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | 現在のオブジェクトのオフセットを指定されたオフセットに置き換えます。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 現在のオブジェクトを、指定されたフォーマットとフォーマットプロバイダーを使用して文字列に変換します。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 現在のオブジェクトを、指定されたフォーマットプロバイダーを使用して文字列に変換します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 現在のオブジェクトを、指定されたフォーマットを使用して文字列に変換します。 |
| [String](../string/) [ToString](./tostring/)() const | 現在のオブジェクトを文字列に変換します。 |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | 現在のオブジェクトを UTC 時間を表すオブジェクトに変換します。 |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Unix エポック開始から経過したミリ秒数を取得します。 |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Unix エポック開始から経過した秒数を取得します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | 指定された文字列を [DateTimeOffset](./) オブジェクトに変換しようとします。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 指定された文字列を、指定されたフォーマットプロバイダーとフォーマットスタイルを使用して [DateTimeOffset](./) オブジェクトに変換しようとします。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 指定された文字列を、指定されたフォーマット群、フォーマットプロバイダー、フォーマットスタイルを使用して [DateTimeOffset](./) オブジェクトに変換しようとします。 |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 指定された文字列を、指定されたフォーマット、フォーマットプロバイダー、フォーマットスタイルを使用して [DateTimeOffset](./) オブジェクトに変換しようとします。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TimeSpan](../timespan/) 構造体を表す [TypeInfo](../typeinfo/) オブジェクトを返します。 |

## フィールド

| Field | Description |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | ティック単位の最大オフセットを取得します。 |
| static [MaxValue](./maxvalue/) | 最大の [DateTimeOffset](./) 値を取得します。 |
| static constexpr [MinOffset](./minoffset/) | ティック単位の最小オフセットを取得します。 |
| static [MinValue](./minvalue/) | 最も早い [DateTimeOffset](./) 値を取得します。 |
| static [UnixEpoch](./unixepoch/) | Unix エポック開始時点を取得します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)