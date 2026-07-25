---
title: HebrewCalendar
second_title: Aspose.Slides for C++ API リファレンス
description: "ヘブライ暦。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション障害が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 144
url: /ja/system.globalization/hebrewcalendar/
---
## HebrewCalendar class


ヘブライ暦。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上で、または operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション失敗が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class HebrewCalendar : public System::Globalization::Calendar
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | 時間点に日数を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | 時間点に時間を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 時間点にミリ秒を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | 時間点に分を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | 時間点に月を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | 時間点に秒を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | 時間点に週を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | 時間点に年を加算します。 |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI 情報。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 現在のオブジェクトのコピーを作成し、共有ポインタとして返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 形式で参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 形式で値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# 形式の浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# 形式の浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | アルゴリズムのタイプを取得します。 |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 現在の時代のインデックスを取得します。 |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 現在の時代の値を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | カレンダーに存在する時代のリストを取得します。 |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | カレンダーが読み取り専用かどうかを確認します。 |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | カレンダーがサポートする最大の時点です。 |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | カレンダーがサポートする最小の時点です。 |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2 桁で表現できる最後の年を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 指定された時点の月の日を取得します。 |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | 指定された時点の曜日を取得します。 |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 指定された時点の年の日を取得します。 |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | 特定の月の日数を取得します。 |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | 特定の月の日数を取得します。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | 特定の年の日数を取得します。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | 特定の年の日数を取得します。 |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 指定された時点の時代を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 指定された時点の時間を取得します。 |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 指定された年のうるう月を取得します。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI 情報。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI 情報。 |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 指定された時点のミリ秒を取得します。 |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 指定された時点の分を取得します。 |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | 指定された時点の月を取得します。 |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | 指定された年の月数を取得します。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | 指定された年の月数を取得します。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | 指定された年の月数を取得します。 |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 指定された時点の秒を取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 指定された時点のその年の週番号を取得します。 |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 指定された時点の年を取得します。 |
|  [HebrewCalendar](./hebrewcalendar/)() | コンストラクタ。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | 日がうるうかどうかを確認します。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 日がうるうかどうかを確認します。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 日がうるうかどうかを確認します。 |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | 月がうるうかどうかを確認します。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | 月がうるうかどうかを確認します。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | 月がうるうかどうかを確認します。 |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | 年がうるうかどうかを確認します。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 年がうるうかどうかを確認します。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 年がうるうかどうかを確認します。 |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 年、月、日、時代の値を確認します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | カレンダーの読み取り専用バージョンを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | 2 桁で表現できる最後の年を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | [DateTime](../../system/datetime/) オブジェクトをコンポーネントから構築します。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) オブジェクトをコンポーネントから構築します。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) オブジェクトをコンポーネントから構築します。 |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax プロパティを使用して年を 4 桁の年に変換します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [HebrewEra](./hebrewera/) | 現在のヘブライ時代。 |

## 参照

* クラス [Calendar](../calendar/)
* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)