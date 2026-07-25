---
title: JapaneseCalendar
second_title: Aspose.Slides for C++ API リファレンス
description: "日本のカレンダーです。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。"
type: docs
weight: 183
url: /ja/system.globalization/japanesecalendar/
---
## JapaneseCalendar クラス

日本の暦です。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使ってこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。

```cpp
class JapaneseCalendar : public System::Globalization::Calendar
```
## メソッド

| メソッド | 説明 |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 現在のオブジェクトのコピーを作成し、shared ポインタとして返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスでオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、二つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、二つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | アルゴリズムタイプを取得します。 |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 現在の時代のインデックスを取得します。 |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 現在の時代の値を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | カレンダーに存在する時代の一覧を取得します。 |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | カレンダーが読み取り専用かどうかを確認します。 |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | カレンダーがサポートする最大の時間点です。 |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | カレンダーがサポートする最小の時間点です。 |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2 桁で表現できる最後の年を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | 指定された時間点の月の日を取得します。 |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | 指定された時間点の曜日を取得します。 |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | 指定された時間点の年の日を取得します。 |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | 特定の月の日数を取得します。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | 特定の月の日数を取得します。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | 特定の月の日数を取得します。 |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | 特定の年の日数を取得します。 |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | 特定の年の日数を取得します。 |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | 特定の年の日数を取得します。 |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 指定された時間点の時代を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 指定された時間点の時間を取得します。 |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 指定された年のうるう月を取得します。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 指定された年のうるう月を取得します。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 指定された年のうるう月を取得します。 |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 指定された時間点のミリ秒を取得します。 |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 指定された時間点の分を取得します。 |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | 指定された時間点の月を取得します。 |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | 指定された年の月数を取得します。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI 情報です。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI 情報です。 |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 指定された時間点の秒を取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。[System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 指定された時間点の年の週を取得します。 |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 指定された時間点の年を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | その日がうるう日かどうかを確認します。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | その日がうるう日かどうかを確認します。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | その日がうるう日かどうかを確認します。 |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | その月がうるう月かどうかを確認します。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | その月がうるう月かどうかを確認します。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | その月がうるう月かどうかを確認します。 |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | その年がうるう年かどうかを確認します。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | その年がうるう年かどうかを確認します。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | その年がうるう年かどうかを確認します。 |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 年、月、日、時代の値を確認します。 |
|  [JapaneseCalendar](./japanesecalendar/)() | コンストラクタです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | カレンダーの読み取り専用バージョンを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2 桁で表現できる最後の年を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared の代わりに）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | [DateTime](../../system/datetime/) オブジェクトをコンポーネントから構築します。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) オブジェクトをコンポーネントから構築します。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) オブジェクトをコンポーネントから構築します。 |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax プロパティを使用して年を 4 桁の年に変換します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Calendar](../calendar/)
* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)