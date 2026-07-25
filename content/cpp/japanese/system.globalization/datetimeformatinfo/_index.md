---
title: DateTimeFormatInfo
second_title: Aspose.Slides for C++ API リファレンス
description: "日付と時刻の書式設定パラメータのセットです。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 66
url: /ja/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo クラス

Set of date and time formatting parameters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | フォーマット情報をクローンします。 |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | デフォルトコンストラクタ。不変のフォーマット情報を構築します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | 省略形の日名を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | 属格形の省略形月名を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | 省略形の月名を取得します。 |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | AM 指定子を取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | フォーマッタに関連付けられたカレンダーを取得します。 |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | フォーマッタに関連付けられたカレンダー週規則を取得します。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | 現在のスレッドの日時フォーマッタを取得します。 |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | 日付区切り文字を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | 日名を取得します。 |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | 週の最初の曜日を取得します。 |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | 完全な日付と時刻のパターンを取得します。 |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | 不変の日時フォーマッタを取得します。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | フォーマッタが読み取り専用かどうかをチェックします。 |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | 長い日付パターンを取得します。 |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | 長い時刻パターンを取得します。 |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | 月日のパターンを取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | 属格形の月名を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | 月名を取得します。 |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | 利用可能な場合、ネイティブカレンダー名を取得します。 |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | PM 指定子を取得します。 |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | RFC1123 パターンを取得します。 |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | 短い日付パターンを取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | 可能な限り最短の日名を取得します。 |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | 短い時刻パターンを取得します。 |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | ソート可能な日付と時刻のパターンを取得します。 |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | 時刻区切り文字を取得します。 |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | ユニバーサルにソート可能な日付と時刻のパターンを取得します。 |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | 年と月のパターンを取得します。 |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | 省略形の曜日名を取得します。 |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | 省略形の時代名を取得します。 |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | 省略形の月名を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | 日付と時刻の値をフォーマットできるすべてのパターンを取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | 指定された書式文字列を使用して日付と時刻の値をフォーマットできるすべてのパターンを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | 曜日名を取得します。 |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | 時代名から時代を取得します。 |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | 時代名を取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | 特定のタイプのフォーマッタを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | フォーマットプロバイダーに関連付けられたフォーマッタを取得します。 |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | うるう年の月名を取得します。 |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | 属格形の月名を取得します。 |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | 月名を取得します。 |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | 指定された曜日の最短名を取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスを表すかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローンを可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | フォーマッタの読み取り専用バージョンを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 省略形の日名を設定します。 |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 属格形の省略形月名を設定します。 |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 省略形の月名を設定します。 |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | AM 指定子を設定します。 |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | フォーマッタに関連付けられたカレンダーを設定します。 |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | フォーマッタに関連付けられたカレンダー週規則を設定します。 |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | 日付区切り文字を設定します。 |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 日名を設定します。 |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | 週の最初の曜日を設定します。 |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | 完全な日付と時刻のパターンを設定します。 |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | 長い日付パターンを設定します。 |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | 長い時刻パターンを設定します。 |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | 月日のパターンを設定します。 |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 属格形の月名を設定します。 |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 月名を設定します。 |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | PM 指定子を設定します。 |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | 短い日付パターンを設定します。 |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 可能な限り最短の日名を設定します。 |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | 短い時刻パターンを設定します。 |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | 時刻区切り文字を設定します。 |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | 年と月のパターンを設定します。 |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | 指定された書式のパターンを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタに設定します（共有ではなく）。コンテナ内のポインタを弱いモードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* クラス [IFormatProvider](../../system/iformatprovider/)
* クラス [ICloneable](../../system/icloneable/)
* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)