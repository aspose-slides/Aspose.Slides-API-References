---
title: StringBuilder
second_title: Aspose.Slides for C++ API リファレンス
description: "文字列を部分ごとに蓄積するバッファです。この型はスタック上の値型として、または System::MakeObject() 関数を使用してヒープに割り当てることができます。オブジェクトが割り当てられたら、これら二つの使用ケースを混同しないでください：スタックに割り当てられたオブジェクトへの SmartPtr ポインタを持つことは厳しく禁止されています。"
type: docs
weight: 326
url: /ja/system.text/stringbuilder/
---
## StringBuilder クラス


[Buffer](../../system/buffer/) を使用して文字列を部分ごとに蓄積します。この型はスタック上の値型として、または [System::MakeObject()](../../system/makeobject/) 関数を使用してヒープ上に割り当てることができます。オブジェクトが割り当てられたら、これら二つの使用方法を混同しないでください：スタックに割り当てられたオブジェクトへの [SmartPtr](../../system/smartptr/) ポインタを持つことは厳しく禁止されています。

```cpp
class StringBuilder : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | ビルダーに文字を追加します。 |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | ビルダーに文字を追加します。 |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | ビルダーに文字配列を追加します。 |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | ビルダーに文字配列のスライスを追加します。 |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | ビルダーに文字列を追加します。 |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | ビルダーに文字列のスライスを追加します。 |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | ビルダーにオブジェクトの文字列表現を追加します。 |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | ビルダーの内容をビルダーに追加します。 |
| [StringBuilder](./) * [Append](./append/)(**float**) | ビルダーに浮動小数点値を追加します。 |
| [StringBuilder](./) * [Append](./append/)(**double**) | ビルダーに浮動小数点値を追加します。 |
| [StringBuilder](./) * [Append](./append/)(int) | ビルダーに整数値を追加します。 |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | ビルダーに算術値を追加します。 |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | ビルダーに列挙値の文字列表現を追加します。 |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | フォーマットされた文字列をビルダーに追加します。 |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | フォーマットされた文字列をビルダーに追加します。 |
| [StringBuilder](./) * [AppendLine](./appendline/)() | 改行文字をビルダーに追加します。 |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | 文字列に改行文字を付加してビルダーに追加します。 |
| [StringBuilder](./) * [Clear](./clear/)() | ビルダーからすべての文字を削除します。 |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | ビルダーのデータを既存の配列位置にコピーします。 |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | [System.Text.StringBuilder](./) のこのインスタンスの容量が指定された値以上であることを保証します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| int [get_Capacity](./get_capacity/)() const | 文字列ビルダーの現在の容量を取得します。 |
| int [get_Length](./get_length/)() const | ビルダーに現在ある文字列の長さを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの C# 類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。[System.Object.GetType()](../../system/object/gettype/) 呼び出しの C# 類似です。 |
| char_t [idx_get](./idx_get/)(int) const | 指定された位置の文字を取得します。 |
| void [idx_set](./idx_set/)(int, char_t) | 指定された位置に文字を設定します。 |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | ビルダーの固定位置に文字列を挿入します。 |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | ビルダーの固定位置に繰り返し文字列を挿入します。 |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | ビルダーの固定位置に文字を挿入します。 |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | ビルダーの固定位置に文字を挿入します。 |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | ビルダーの固定位置に値を挿入します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 対象タイプで記述された型のインスタンスであるかどうかオブジェクトをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの C# 類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| char_t [operator[]](./operator[]/)(int) const | 指定された位置の文字を取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | ビルダーからフラグメントを削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ビルダー全体で部分文字列を置換します。 |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | ビルダーの範囲内で部分文字列を置換します。 |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | ビルダー全体で文字を置換します。 |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | ビルダーの範囲内で文字を置換します。 |
| void [set_Capacity](./set_capacity/)(int) | 文字列ビルダーの現在の容量を設定します。 |
| void [set_Length](./set_length/)(int) | 文字列ビルダーを指定された長さに切り詰めるか拡張します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [StringBuilder](./stringbuilder/)() | コンストラクタ。 |
|  [StringBuilder](./stringbuilder/)(int) | コンストラクタ。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | コンストラクタ。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | コンストラクタ。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | コンストラクタ。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | ビルダーに現在含まれる文字列を取得します。 |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | ビルダーに現在含まれる部分文字列を取得します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
|  [~StringBuilder](./~stringbuilder/)() | デストラクタ。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Text](../)
* ライブラリ [Aspose.Slides](../../)