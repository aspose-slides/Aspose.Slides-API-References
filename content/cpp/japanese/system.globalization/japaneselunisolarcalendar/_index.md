---
title: JapaneseLunisolarCalendar
second_title: Aspose.Slides の C++ API リファレンス
description: "日本の太陰太陽暦です。未実装です。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上で、または operator new を使用してインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを引数として関数に渡すようにしてください。"
type: docs
weight: 196
url: /ja/system.globalization/japaneselunisolarcalendar/
---
## JapaneseLunisolarCalendar クラス

Japanese lunisolar calendar. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JapaneseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## メソッド

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | 時間点に日数を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | 時間点に時間を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 時間点にミリ秒を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | 時間点に分を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | 時間点に月数を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | 時間点に秒数を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | 時間点に週数を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | 時間点に年数を加算します。 |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI 情報です。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 現在のオブジェクトのコピーを作成し、shared_ptr を返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスでオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI 情報です。 |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 現在の時代のインデックスを取得します。 |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 現在の時代の値を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | カレンダーに存在する時代のリストを取得します。 |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | カレンダーが読み取り専用かどうかを確認します。 |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | カレンダーがサポートする最大の時間点です。 |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | カレンダーがサポートする最小の時間点です。 |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2 桁で表現できる最終年を取得します。 |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | 天干を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 指定された時間点の月の日を取得します。 |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | 指定された時間点の曜日を取得します。 |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 指定された時間点の年の日を取得します。 |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | 特定の月の日数を取得します。 |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | 特定の月の日数を取得します。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | 特定の年の日数を取得します。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | 特定の年の日数を取得します。 |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 指定された時間点の時代を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 指定された時間点の時間を取得します。 |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 指定された年のうるう月を取得します。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI 情報です。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI 情報です。 |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 指定された時間点のミリ秒を取得します。 |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 指定された時間点の分を取得します。 |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | 指定された時間点の月を取得します。 |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | 指定された年の月数を取得します。 |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | 指定された年の月数を取得します。 |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 指定された時間点の秒を取得します。 |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | 六十干支周期の年を取得します。 |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | 地支を取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 指定された時間点の週番号を取得します。 |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | 指定された時間点の年を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | 日がうるう日かどうかを確認します。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 日がうるう日かどうかを確認します。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 日がうるう日かどうかを確認します。 |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | 月がうるう月かどうかを確認します。 |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | 月がうるう月かどうかを確認します。 |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | 年がうるう年かどうかを確認します。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 年がうるう年かどうかを確認します。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 年がうるう年かどうかを確認します。 |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 年、月、日、時代の値を確認します。 |
|  [JapaneseLunisolarCalendar](./japaneselunisolarcalendar/)() | コンストラクタ。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | カレンダーの読み取り専用バージョンを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ shared 参照カウントを減少させます。 |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2 桁で表現できる最終年を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | shared 参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | shared 参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | shared 参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | コンポーネントから [DateTime](../../system/datetime/) オブジェクトを構築します。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | コンポーネントから [DateTime](../../system/datetime/) オブジェクトを構築します。 |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax プロパティを使用して年を 4 桁の年に変換します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| Field | Description |
| --- | --- |
| static constexpr [JapaneseEra](./japaneseera/) | 現在の日本の時代。 |

## 参照

* クラス [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)