---
title: FontFallBackRule
second_title: Aspose.Slides for C++ API リファレンス
description: フォントフォールバックルールを表します
type: docs
weight: 937
url: /ja/aspose.slides/fontfallbackrule/
---
## FontFallBackRule クラス


フォントフォールバックルールを表します

```cpp
class FontFallBackRule : public Aspose::Slides::IFontFallBackRule
```

## メソッド

| Method | Description |
| --- | --- |
| void [AddFallBackFonts](./addfallbackfonts/)([System::String](../../system/string/)) override | フォールバックフォントのリストに新しいフォントを追加します。 |
| void [AddFallBackFonts](./addfallbackfonts/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | フォールバックフォントのリストに新しいフォントを追加します。 |
| void [Clear](./clear/)() override | リストからすべてのフォントを削除します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::String](../../system/string/)) | 新しいインスタンスを作成します。 |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | 新しいインスタンスを作成します。 |
| **int32_t** [get_Count](./get_count/)() override | 範囲に実際に定義されているフォントの数を取得します。読み取り専用 **int32_t**。 |
| **uint32_t** [get_RangeEndIndex](./get_rangeendindex/)() override | 連続する Unicode 範囲の最後のインデックスを取得します。 |
| **uint32_t** [get_RangeStartIndex](./get_rangestartindex/)() override | 連続する Unicode 範囲の最初のインデックスを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナロジーです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナロジーです。 |
| [System::String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) override | 指定されたインデックスのフォント名を取得します。読み取り専用 [IFontFallBackRule](../ifontfallbackrule/)。 |
| **int32_t** [IndexOf](./indexof/)([System::String](../../system/string/)) override | コレクション内の指定されたルールのインデックスを返します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナロジーです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナロジーです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| void [Remove](./remove/)([System::String](../../system/string/)) override | リストから特定のフォールバックフォントの最初の出現を削除します。 |
| void [RemoveAt](./removeat/)(**int32_t**) override | リストの指定インデックスにあるフォールバックフォントを削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定値だけ共有参照カウンタを減少させます。 |
| void [set_RangeEndIndex](./set_rangeendindex/)(**uint32_t**) | 連続する Unicode 範囲の最後のインデックスを取得します。 |
| void [set_RangeStartIndex](./set_rangestartindex/)(**uint32_t**) | 連続する Unicode 範囲の最初のインデックスを取得します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)() override | このルールのすべてのフォールバックフォントの配列を作成して返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | リストの指定範囲からすべてのフォールバックフォントの配列を作成して返します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナロジーです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* クラス [IFontFallBackRule](../ifontfallbackrule/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)