---
title: StringComparer
second_title: Aspose.Slides for C++ APIリファレンス
description: "異なる比較モードを使用して文字列を比較します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使ってこの型のインスタンスを作成しないでください。そうするとランタイムエラーやアサーション障害が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡して使用してください。"
type: docs
weight: 1288
url: /ja/system/stringcomparer/
---
## StringComparer クラス

異なる比較モードを使用して文字列を比較します。 このクラスのオブジェクトは [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上で、または operator new を使用してこの型のインスタンスを作成しないでください。そうするとランタイムエラーやアサーション障害が発生します。 常にこのクラスを [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| int [Compare](./compare/)([args_type](./args_type/), [args_type](./args_type/)) const override | 現在の設定を使用して 2 つの文字列を比較します。 |
| static [StringComparerPtr](../stringcomparerptr/) [Create](./create/)(const [System::SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **bool**) | カルチャー固有の比較子を作成します。 |
| **bool** [Equals](./equals/)([String](../string/), [String](../string/)) const override | 現在の設定を使用して 2 つの文字列が等しいかどうかを確認します。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。 IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN が等しいとみなされます。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。 IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN が等しいとみなされます。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCulture](./get_currentculture/)() | 現在のカルチャー比較子のシングルトンです。 |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | 現在のカルチャーで大文字小文字を区別しない比較子のシングルトンです。 |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCulture](./get_invariantculture/)() | 不変カルチャー比較子のシングルトンです。 |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | 不変カルチャーで大文字小文字を区別しない比較子のシングルトンです。 |
| static [StringComparerPtr](../stringcomparerptr/) [get_Ordinal](./get_ordinal/)() | 順序比較子のシングルトンです。 |
| static [StringComparerPtr](../stringcomparerptr/) [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | 順序で大文字小文字を区別しない比較子のシングルトンです。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| int [GetHashCode](./gethashcode/)([String](../string/)) const override | 文字列のハッシュコードを取得します。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../object/lock/)() | C# の lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照で比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
|  [RTTI_INFO_TEMPLATE_CLASS](../../system.collections.generic/iequalitycomparer/rtti_info_template_class/)([System::Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<T\>, System::BaseTypesInfo\<[System::Object](../object/)\>) | RTTI 情報です。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 構文を実装します。 |
| void [Unlock](../object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウンタをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウンタをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [args_type](./args_type/) | 引数の型です。 |

## 参照

* クラス [Object](../object/)
* クラス [IComparer](../../system.collections.generic/icomparer/)
* クラス [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)