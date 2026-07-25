---
title: NumberFormatInfo
second_title: Aspose.Slides の C++ API リファレンス
description: "数値の書式設定方法に関する情報を保持します。設定子操作は読み取り専用でないオブジェクトでのみ有効です。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や new 演算子でこの型のインスタンスを作成しないでください。実行時エラーやアサーションの失敗につながります。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 248
url: /ja/system.globalization/numberformatinfo/
---
## NumberFormatInfo クラス

数値の書式設定方法に関する情報を保持します。設定子操作は読み取り専用でないオブジェクトでのみ有効です。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や new 演算子を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション失敗が発生する可能性があります。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | フォーマット情報を複製します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | 通貨の小数桁数を取得します。 |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | 通貨の小数区切り記号を取得します。 |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | 通貨のグループ区切り記号を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | グループあたりの通貨小数桁数を取得します。 |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | 通貨の負のパターンを取得します。 |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | 通貨の正のパターンを取得します。 |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | 通貨記号を取得します。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | 現在のスレッドのカルチャで定義された数値書式情報を取得します。 |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | 桁の形状表示方法を指定する値を取得します。 |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | 不変カルチャで定義された数値書式情報を取得します。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 書式が読み取り専用かどうかをチェックします。 |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | NaN 記号を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | 数字シンボル（0 から 9）を取得します。 |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | 負の無限大記号を取得します。 |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | 負の符号を取得します。 |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | 小数桁数を取得します。 |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | 小数区切り記号を取得します。 |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | 桁グループ区切り記号を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | グループあたりの桁数を取得します。 |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | 負の数パターンを取得します。 |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | パーセント値の小数桁数を取得します。 |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | パーセンテージ値の小数区切り記号を取得します。 |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | パーセンテージ値のグループ区切り記号を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | パーセンテージ値グループあたりの桁数を取得します。 |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | パーセンテージの負のパターンを取得します。 |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | パーセンテージの正のパターンを取得します。 |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | パーセンテージ記号を取得します。 |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | パーミル記号を取得します。 |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | 正の無限大記号を取得します。 |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | 正の符号を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | 特定の型のフォーマッタを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | フォーマットプロバイダーに関連付けられたフォーマッタを取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [NumberFormatInfo](./numberformatinfo/)() | デフォルトコンストラクタ（不変 [NumberFormatInfo](./)）。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | フォーマッタの読み取り専用バージョンを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | 通貨の小数桁数を設定します。 |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | 通貨の小数区切り記号を設定します。 |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | 通貨のグループ区切り記号を設定します。 |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | グループあたりの通貨小数桁数を設定します。 |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | 通貨の負のパターンを設定します。 |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | 通貨の正のパターンを設定します。 |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | 通貨記号を設定します。 |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | 桁の形状表示方法を指定する値を設定します。 |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | NaN 記号を設定します。 |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 数字シンボル（0 から 9）を設定します。 |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | 負の無限大記号を設定します。 |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | 負の符号を設定します。 |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | 小数桁数を設定します。 |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | 小数区切り記号を設定します。 |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | 桁グループ区切り記号を設定します。 |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | グループあたりの桁数を設定します。 |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | 負の数パターンを設定します。 |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | パーセント値の小数桁数を設定します。 |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | パーセンテージ値の小数区切り記号を設定します。 |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | パーセンテージ値のグループ区切り記号を設定します。 |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | パーセンテージ値グループあたりの桁数を設定します。 |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | パーセンテージの負のパターンを設定します。 |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | パーセンテージの正のパターンを設定します。 |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | パーセンテージ記号を設定します。 |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | パーミル記号を設定します。 |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | 正の無限大記号を設定します。 |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | 正の符号を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* クラス [IFormatProvider](../../system/iformatprovider/)
* クラス [ICloneable](../../system/icloneable/)
* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)