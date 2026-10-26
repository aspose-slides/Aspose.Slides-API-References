---
title: StreamWriter
second_title: Aspose.Slides for C++ API リファレンス
description: "バイト ストリームに文字を書き込むライターを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。"
type: docs
weight: 391
url: /ja/system.io/streamwriter/
---
## StreamWriter クラス


バイト ストリームに文字を書き込むライターを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。

```cpp
class StreamWriter : public System::IO::TextWriter
```

## メソッド

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | ストリームを閉じ、取得したリソースを解放します。 |
| void [Dispose](./dispose/)() override | 現在のオブジェクトが使用しているすべてのリソースを解放し、基礎となるストリームを閉じます。 |
| virtual void [Dispose](./dispose/)(**bool**) | 現在のオブジェクトが使用しているすべてのリソースを解放し、基礎となるストリームを閉じます。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途限定です。 |
| void [Flush](./flush/)() override | バッファの内容を基礎となるストリームにフラッシュし、続いてそのストリーム自体をフラッシュします。 |
| **bool** [get_AutoFlush](./get_autoflush/)() const | [StreamWriter](./) が [StreamWriter::Write](./write/) メソッド呼び出しごとにデータを基礎となるストリームへフラッシュするかどうかを示す値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | 基礎となるストリームを表すオブジェクトへの共有ポインタを返します。 |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | 現在使用されているエンコーディングを返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | 現在使用されている [IFormatProvider](../../system/iformatprovider/) オブジェクトを返します。 |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | 現在使用されている [IFormatProvider](../../system/iformatprovider/) オブジェクトを返します。 |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | 改行文字列を返します。 |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | 改行文字列を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドに相当し、カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しに相当します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子に相当します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドに相当し、カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | [StreamWriter](./) が [StreamWriter::Write](./write/) メソッド呼び出しごとにデータを基礎となるストリームへフラッシュするかどうかを示す値を返します。 |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | 改行文字列を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | [StreamWriter](./) オブジェクトのインスタンスを作成します。このオブジェクトは UTF-8 エンコーディングとデフォルトサイズ 1024 バイトのバッファを使用して、指定された基礎ストリームに文字を書き込みます。 |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | [StreamWriter](./) オブジェクトのインスタンスを作成します。このオブジェクトは指定されたエンコーディングとデフォルトサイズ 1024 バイトのバッファを使用して、指定された基礎ストリームに文字を書き込みます。 |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | [StreamWriter](./) オブジェクトのインスタンスを作成します。指定されたエンコーディングと指定サイズのバッファを使用して、指定された基礎ストリームに文字を書き込みます。パラメータは、[StreamWriter](./) オブジェクトが破棄される際に基礎ストリームを閉じるかどうかを指定します。 |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | [StreamWriter](./) オブジェクトのインスタンスを作成します。このオブジェクトは UTF-8 エンコーディングとデフォルトサイズ 1024 バイトのバッファを使用して、指定されたファイルに文字を書き込みます。 |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | [StreamWriter](./) オブジェクトのインスタンスを作成します。指定されたエンコーディングとデフォルトサイズ 1024 バイトのバッファを使用して、指定されたファイルに文字を書き込みます。パラメータはデータをファイルに追記するか上書きするかを指定します。 |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | [StreamWriter](./) オブジェクトのインスタンスを作成します。指定されたエンコーディングとバッファサイズを使用して、指定されたファイルに文字を書き込みます。パラメータはデータをファイルに追記するか上書きするかを指定します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドに相当し、カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Write](./write/)(char_t) override | 指定された文字をストリームに書き込みます。 |
| void [Write](./write/)(const [String](../../system/string/)\&) override | 指定された文字列をストリームに書き込みます。 |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | 指定されたオブジェクトの文字列表現をストリームに書き込みます。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | 指定された配列のすべての文字をストリームに書き込みます。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 指定された文字配列から UTF-16 文字の指定サブレンジを書き込みます。 |
| void [Write](./write/)(const char_t *) override | 指定された C 文字列をストリームに書き込みます。 |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | 指定されたオブジェクトの文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(**bool**) | 指定されたブール値の文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) オブジェクトの文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(**double**) | 指定された倍精度浮動小数点値の文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(int) | 指定された 32 ビット整数値の文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(**int64_t**) | 指定された 64 ビット整数値の文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(**float**) | 指定された単精度浮動小数点値の文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | 指定された符号なし 32 ビット整数値の文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | 指定された符号なし 64 ビット整数値の文字列表現をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | [TypeInfo](../../system/typeinfo/) オブジェクトの文字列表現をストリームに書き込みます。 |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | 指定されたフォーマットに従ってフォーマットされた値を書き込みます。 |
| void [WriteLine](./writeline/)() override | 改行文字をストリームに書き込みます。 |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | 指定された文字列と改行文字をストリームに書き込みます。 |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | 指定されたオブジェクトの文字列表現と改行文字をストリームに書き込みます。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | 指定された配列のすべての文字と改行文字をストリームに書き込みます。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 指定された文字配列から UTF-16 文字の指定サブレンジと改行文字を書き込みます。 |
| void [WriteLine](./writeline/)(const char_t *) override | 指定された C 文字列と改行文字を書き込みます。 |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | 指定されたオブジェクトの文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | 指定されたブール値の文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | 指定された文字と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) オブジェクトの文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | 指定された倍精度浮動小数点値の文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(int) | 指定された 32 ビット整数値の文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | 指定された 64 ビット整数値の文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | 指定された単精度浮動小数点値の文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | 指定された符号なし 32 ビット整数値の文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | 指定された符号なし 64 ビット整数値の文字列表現と改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | [TypeInfo](../../system/typeinfo/) オブジェクトの文字列表現と改行文字を書き込みます。 |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 指定されたフォーマットに従ってフォーマットされた値と改行文字を書き込みます。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |
|  [~StreamWriter](./~streamwriter/)() | デストラクタ。 |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | デストラクタ。 |

## 参照

* クラス [TextWriter](../textwriter/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)