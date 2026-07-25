---
title: CompareInfo
second_title: Aspose.Slides for C++ API リファレンス
description: "カルチャーに依存した文字列比較を行います。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 40
url: /ja/system.globalization/compareinfo/
---
## CompareInfo クラス

カルチャーに依存した文字列比較を行います。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class CompareInfo : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | 文字列を比較します。実装されていません。 |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | 文字列を比較します。Ordinal と OrdinalIgnoreCase モードのみがサポートされています。 |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | 1つの文字列のセクションと別の文字列のセクションを比較します。実装されていません。 |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | 文字列比較メソッドを使用して、1つの文字列の末端セクションと別の文字列の末端セクションを比較します。実装されていません。 |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | 1つの文字列の末端セクションと別の文字列の末端セクションを比較します。実装されていません。 |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | 文字列比較メソッドを使用して、1つの文字列のセクションと別の文字列のセクションを比較します。実装されていません。 |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | RTTI 情報。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみで使用されます。 |
| int [get_LCID](./get_lcid/)() const | 比較対象に関連付けられたカルチャーの LCID を取得します。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | 比較対象に関連付けられたカルチャーの名前を取得します。 |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | ソートバージョンに関する情報を取得します。 |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | [CompareInfo](./) を取得します。指定されたカルチャーに関連付けられ、指定されたアセンブリで文字列比較メソッドを使用します。 |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | [CompareInfo](./) を取得します。指定されたカルチャーに関連付けられ、指定されたアセンブリで文字列比較メソッドを使用します。 |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | [CompareInfo](./) を取得します。指定されたカルチャーに関連付けられます。 |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | [CompareInfo](./) を取得します。指定されたカルチャーに関連付けられます。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | 指定された比較オプションに基づいて文字列ハッシュコードを取得します。 |
| int [GetHashCode](./gethashcode/)() const override | [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの C# アナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | 指定された文字列に対して、指定された比較オプションを使用して [SortKey](../sortkey/) オブジェクトを取得します。 |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | 指定された文字列に対して [SortKey](../sortkey/) オブジェクトを取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | 部分文字列を検索します。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | 部分文字列を検索します。Ordinal モードのみがサポートされています。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | 部分文字列を検索します。Ordinal モードのみがサポートされています。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | 指定された文字を検索します。Ordinal モードのみがサポートされています。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | 部分文字列を検索します。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | 指定された文字を検索します。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | 部分文字列を検索します。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | 指定された文字を検索します。Ordinal モードのみがサポートされています。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | 指定された文字を検索します。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | 指定された文字を検索します。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | 部分文字列を検索します。Ordinal モードのみがサポートされています。 |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | 指定された文字を検索します。Ordinal モードのみがサポートされています。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが対象タイプであるかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | 指定された比較オプションを使用して、指定された文字列が指定されたプレフィックスで始まるかどうかをチェックします。 |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | 指定された文字列が指定されたプレフィックスで始まるかどうかをチェックします。 |
| static **bool** [IsSortable](./issortable/)(char16_t) | 指定された文字がソート可能かどうかをチェックします。 |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | 指定された文字列がソート可能かどうかをチェックします。 |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | 指定された比較オプションを使用して、指定された文字列が指定されたサフィックスで終わるかどうかをチェックします。 |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | 指定された文字列が指定されたサフィックスで終わるかどうかをチェックします。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | 指定された部分文字列の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | 指定された比較オプションを使用して、指定された部分文字列の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | 指定された比較オプションを使用して、指定された文字の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | 指定された文字列の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | 指定された比較オプションを使用して、指定された文字列の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | 指定された比較オプションを使用して、指定された文字の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | 指定された文字列の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | 指定された文字の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | 指定された比較オプションを使用して、指定された文字列の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | 指定された比較オプションを使用して、指定された文字の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | 指定された文字の最後の出現箇所を検索します。 |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | 指定された文字の最後の出現箇所を検索します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Globalization](../)
* ライブラリ [Aspose.Slides](../../)