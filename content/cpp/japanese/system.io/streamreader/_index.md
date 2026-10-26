---
title: StreamReader
second_title: Aspose.Slides for C++ API リファレンス
description: "バイトストリームから文字を読み取るリーダーを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。"
type: docs
weight: 378
url: /ja/system.io/streamreader/
---
## StreamReader クラス


バイトストリームから文字を読み取るリーダーを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡すようにしてください。

```cpp
class StreamReader : public System::IO::TextReader
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Close](./close/)() override | 現在のストリームと基になるストリームを閉じます。 |
| virtual void [Dispose](./dispose/)(**bool**) | 現在のオブジェクトが使用しているすべてのリソースを解放し、基になるストリームを閉じます。 |
| void [Dispose](./dispose/)() override | 現在のオブジェクトが使用しているすべてのリソースを解放し、基になるストリームを閉じます。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | 基になるストリームを表すオブジェクトへの共有ポインタを返します。 |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | 現在使用されているエンコーディングを返します。 |
| **bool** [get_EndOfStream](./get_endofstream/)() | ストリームの終端に到達したかどうかを示す値を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| int [Peek](./peek/)() override | ストリームの読み取りカーソルを変更せずに、ストリームから単一文字を読み取ります。 |
| int [Read](./read/)() override | ストリームから単一文字を読み取ります。 |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | ストリームから指定された文字数を読み取り、UTF-16 エンコーディングに変換し、結果の UTF-16 文字を指定された位置から開始する指定された文字配列に書き込みます。 |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 現在のテキストリーダーから指定された最大文字数を読み取り、指定されたインデックスから開始してバッファにデータを書き込みます。 |
| [String](../../system/string/) [ReadLine](./readline/)() override | 現在の行の終端までストリームから文字を読み取ります。 |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | ストリームの終端まで文字を読み取ります。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さないでください；代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出さないでください；代わりにスマートポインタまたは ThisProtector を使用してください。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定された基になるストリームから UTF-8 エンコーディングを使用し、デフォルトサイズ 1024 バイトのバッファで文字を読み取ります。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定された基になるストリームから UTF-8 エンコーディングを使用し、デフォルトサイズ 1024 バイトのバッファで文字を読み取ります。パラメータはバイトオーダーマーク検出を有効にするかどうかを指定します。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定された基になるストリームから指定されたエンコーディングを使用し、デフォルトサイズ 1024 バイトのバッファで文字を読み取ります。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定された基になるストリームから指定されたエンコーディングを使用し、デフォルトサイズ 1024 バイトのバッファで文字を読み取ります。パラメータはバイトオーダーマーク検出を有効にするかどうかを指定します。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定された基になるストリームから指定されたエンコーディングを使用し、指定されたサイズのバッファで文字を読み取ります。パラメータはバイトオーダーマーク検出を有効にするかどうかを指定します。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定されたファイルから UTF-8 エンコーディングを使用し、デフォルトサイズ 4096 バイトのバッファで文字を読み取ります。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定されたファイルから UTF-8 エンコーディングを使用し、デフォルトサイズ 4096 バイトのバッファで文字を読み取ります。パラメータはバイトオーダーマーク検出を有効にするかどうかを指定します。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定されたファイルから指定されたエンコーディングを使用し、デフォルトサイズ 4096 バイトのバッファで文字を読み取ります。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定された基になるストリームから指定されたエンコーディングを使用し、デフォルトサイズ 4096 バイトのバッファで文字を読み取ります。パラメータはバイトオーダーマーク検出を有効にするかどうかを指定します。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | [StreamReader](./) オブジェクトのインスタンスを構築します。このオブジェクトは指定されたファイルから指定されたエンコーディングを使用し、指定されたサイズのバッファで文字を読み取ります。パラメータはバイトオーダーマーク検出を有効にするかどうかを指定します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さないでください；代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さないでください；代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
|  [~StreamReader](./~streamreader/)() | デストラクタ。 |

## 参照

* クラス [TextReader](../textreader/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)