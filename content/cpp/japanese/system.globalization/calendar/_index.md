---
title: Calendar
second_title: Aspose.Slides for C++ API リファレンス
description: "日付の処理、計算、フォーマットなどを定義する Calendar。Setter 操作は読み取り専用でないオブジェクトでのみ有効です。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 1
url: /ja/system.globalization/calendar/
---
## Calendar クラス

[Calendar](./) は、日付の処理、計算、フォーマットなどを定義します。Setter 操作は、読み取り専用でないオブジェクトでのみ有効です。このクラスのオブジェクトは、[System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこのタイプのインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。

```cpp
class Calendar : public System::ICloneable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | 時間ポイントに日数を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | 時間ポイントに時間を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 時間ポイントにミリ秒を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | 時間ポイントに分を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | 時間ポイントに月を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | 時間ポイントに秒を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | 時間ポイントに週を加算します。 |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | 時間ポイントに年を加算します。 |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | RTTI 情報。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | 現在のオブジェクトのコピーを作成し、それへの共有ポインタを返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみに使用されます。 |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | アルゴリズムのタイプを取得します。 |
| int [get_CurrentEra](./get_currentera/)() const | 現在の時代のインデックスを取得します。 |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | 現在の時代の値を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | カレンダーに存在する時代のリストを取得します。 |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | カレンダー識別子を取得します。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | カレンダーが読み取り専用かどうかを確認します。 |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | カレンダーがサポートする最大の時間点です。 |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | カレンダーがサポートする最小の時間点です。 |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | 2 桁で表現できる最後の年を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | 指定された時間点の月の日を取得します。 |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | 指定された時間点の曜日を取得します。 |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | 指定された時間点の年の日を取得します。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | 特定の月の日数を取得します。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | 特定の月の日数を取得します。 |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | 特定の年の日数を取得します。 |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | 特定の年の日数を取得します。 |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | 指定された時間点の時代を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を有効にします。 |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | 指定された時間点の時間を取得します。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 指定された年の閏月を取得します。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 指定された年の閏月を取得します。 |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | 指定された時間点のミリ秒を取得します。 |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | 指定された時間点の分を取得します。 |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | 指定された時間点の月を取得します。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | 指定された年の月数を取得します。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | 指定された年の月数を取得します。 |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | 指定された時間点の秒を取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 指定された時間点の年の週を取得します。 |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | 指定された時間点の年を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるか確認します。C# の 'is' 演算子の類似です。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | その日が閏日かどうかをチェックします。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | その日が閏日かどうかをチェックします。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | その月が閏月かどうかをチェックします。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | その月が閏月かどうかをチェックします。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | その年が閏年かどうかをチェックします。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | その年が閏年かどうかをチェックします。 |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | 年、月、日、時代の値をチェックします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を有効にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | カレンダーの読み取り専用バージョンを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | 2 桁で表現できる最後の年を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) オブジェクトをコンポーネントから構築します。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) オブジェクトをコンポーネントから構築します。 |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | TwoDigitYearMax プロパティを使用して年を 4 桁の年に変換します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ICloneable](../../system/icloneable/)
* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)