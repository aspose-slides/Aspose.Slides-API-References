---
title: ConsoleOutput
second_title: Aspose.Slides for C++ API リファレンス
description: "標準出力ストリームを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 209
url: /ja/system/consoleoutput/
---
## ConsoleOutput クラス


標準出力ストリームを表します。このクラスのオブジェクトは [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。このクラスは常に [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | ストリームを閉じ、取得したリソースを解放します。 |
| void [Dispose](../../system.io/textwriter/dispose/)() override | 現在のオブジェクトが使用しているすべてのリソースを解放し、基底ストリームを閉じます。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 参照型オブジェクトを C# スタイルで比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 値型オブジェクトを C# スタイルで比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくないはずですが、ここでは 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくないはずですが、ここでは 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual void [Flush](../../system.io/textwriter/flush/)() | バッファの内容を基底ストリームにフラッシュします。 |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | 常に ASCII エンコーディングを返します。 |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | 現在使用中の [IFormatProvider](../iformatprovider/) オブジェクトを返します。 |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | 現在使用中の [IFormatProvider](../iformatprovider/) オブジェクトを返します。 |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | 行終端文字列を返します。 |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | 行終端文字列を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# の [Object.GetHashCode()](../object/gethashcode/) メソッドに相当します。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../object/gettype/) 呼び出しに相当します。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子に相当します。 |
| void [Lock](../object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|  [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | 行終端文字列を設定します。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# の [Object.ToString()](../object/tostring/) メソッドに相当します。カスタムオブジェクトを文字列に変換することが可能です。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# の typeof([System.Object](../object/)) 構文を実装します。 |
| void [Unlock](../object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Write](./write/)(**bool**) override | 指定された bool 値の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | 指定されたオブジェクトの文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(char_t) override | 指定された文字値を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)([Decimal](../decimal/)) override | [Decimal](../decimal/) の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(**double**) override | 倍精度浮動小数点値の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(**int32_t**) override | 32ビット整数値の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(**int64_t**) override | 64ビット整数値の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(**float**) override | 単精度浮動小数点値の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(const [String](../string/)\&) override | 指定された文字列オブジェクトを現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(**uint32_t**) override | 符号なし 32 ビット整数値の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(**uint64_t**) override | 符号なし 64 ビット整数値の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | 指定された文字配列の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 指定された文字配列の値の範囲の文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(const char_t *) override | 指定された C 文字列を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | 指定された [TypeInfo](../typeinfo/) オブジェクトの文字列表現を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | 指定された 32 ビット整数値の文字列表現を書き込みます。 |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | 指定された書式に従って指定された値を書き込みます。 |
| void [WriteLine](./writeline/)() override | 現在の行終端文字を現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | 指定されたオブジェクトの文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(**bool**) override | 指定された bool 値の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(char_t) override | 指定された文字値を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | [Decimal](../decimal/) の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(**double**) override | 倍精度浮動小数点値の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(int) override | 32 ビット整数値の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(**int64_t**) override | 64 ビット整数値の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(**float**) override | 単精度浮動小数点値の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | 指定された文字列オブジェクトを、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(**uint32_t**) override | 符号なし 32 ビット整数値の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(**uint64_t**) override | 符号なし 64 ビット整数値の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | 指定された文字配列の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 指定された文字配列の値の範囲の文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(const char_t *) override | 指定された C 文字列を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | 指定された [TypeInfo](../typeinfo/) オブジェクトの文字列表現を、現在の行終端文字とともに現在のオブジェクトが表す出力ストリームに出力します。 |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | 指定された書式に従って指定された値を書き込み、行終端文字とともにストリームへ出力します。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | デストラクタ。 |

## 参照

* クラス [TextWriter](../../system.io/textwriter/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)