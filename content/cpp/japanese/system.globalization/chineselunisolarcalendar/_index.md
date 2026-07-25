---
title: ChineseLunisolarCalendar
second_title: Aspose.Slides for C++ API リファレンス
description: "中国の太陰陽暦。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。そうするとランタイムエラーやアサーションフォルトが発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 27
url: /ja/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar クラス

Chinese lunisolar calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | 時間点に日数を加えます。 |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | 時間点に時間を加えます。 |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 時間点にミリ秒を加えます。 |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | 時間点に分を加えます。 |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | 時間点に月を加えます。 |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | 時間点に秒を加えます。 |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | 時間点に週を加えます。 |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | 時間点に年を加えます。 |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI情報。 |
|  [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | デフォルトコンストラクタ。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 現在のオブジェクトのコピーを作成し、共有ポインタを返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。2つの NaN は IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。2つの NaN は IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI情報。 |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 現在の時代のインデックスを取得します。 |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 現在の時代の値を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | カレンダーに存在する時代のリストを取得します。 |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | カレンダーが読み取り専用かどうかを確認します。 |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | カレンダーがサポートする最大の時間点です。 |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | カレンダーがサポートする最小の時間点です。 |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2桁で表現できる最後の年を取得します。 |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | 天干を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 指定された時間点の月の日を取得します。 |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | 指定された時間点の曜日を取得します。 |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 指定された時間点の年の日を取得します。 |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | 特定の月の日数を取得します。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | 特定の月の日数を取得します。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | 特定の月の日数を取得します。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | 特定の年の日数を取得します。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | 特定の年の日数を取得します。 |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 指定された時間点の時代を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 指定された時間点の時間を取得します。 |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 指定された年のうるう月を取得します。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 指定された年のうるう月を取得します。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 指定された年のうるう月を取得します。 |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 指定された時間点のミリ秒を取得します。 |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 指定された時間点の分を取得します。 |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | 指定された時間点の月を取得します。 |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | 指定された年の月数を取得します。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI情報。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI情報。 |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 指定された時間点の秒を取得します。 |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | 六十干支の年を取得します。 |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | 地支を取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 指定された時間点の年の週を取得します。 |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 指定された時間点の年を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
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
| void [Lock](../../system/object/lock/)() | C# lock() 文のロック処理を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | カレンダーの読み取り専用バージョンを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2桁で表現できる最後の年を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) オブジェクトを構成要素から構築します。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) オブジェクトを構成要素から構築します。 |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax プロパティを使用して年を 4 桁の年に変換します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除処理を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | 現在の中国の時代。 |

## 参照

* クラス [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)