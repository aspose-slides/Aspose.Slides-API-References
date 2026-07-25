---
title: BinaryReader
second_title: Aspose.Slides の C++ API リファレンス
description: "特定のエンコーディングでプリミティブ データ型をバイナリ データとして読み取るリーダーを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション障害が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡してください。"
type: docs
weight: 92
url: /ja/system.io/binaryreader/
---
## BinaryReader クラス

特定のエンコーディングでプリミティブ データ型をバイナリ データとして読み取るリーダーを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション障害が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。

```cpp
class BinaryReader : public System::IDisposable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | [BinaryReader](./) クラスのインスタンスを構築します。指定されたストリームからデータを読み取り、UTF-8 エンコーディングを使用します。 |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | [BinaryReader](./) クラスのインスタンスを構築します。指定されたストリームからデータを読み取り、指定されたエンコーディングを使用します。 |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | [BinaryReader](./) クラスのインスタンスを構築します。指定されたストリームからデータを読み取り、指定されたエンコーディングを使用します。 |
| virtual void [Close](./close/)() | 現在の [BinaryReader](./) オブジェクトと基になる入力ストリームを閉じます。 |
| void [Dispose](./dispose/)() override | 現在のオブジェクトが使用しているすべてのリソースを解放し、基になるストリームを閉じます。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 の規定では NaN はどの値とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 の規定では NaN はどの値とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用のみです。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | 入力ストリームを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) 監視オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| virtual int [PeekChar](./peekchar/)() | ストリームの読み取りカーソルを変更せずに、入力ストリームから単一の文字を読み取ります。 |
| virtual int [Read](./read/)() | 入力ストリームから単一の文字を読み取ります。 |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 入力ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 入力ストリームから指定された文字数を読み取り、UTF-16 エンコーディングに変換し、結果の UTF-16 文字を指定された位置から始まる指定された文字配列に書き込みます。 |
| virtual **bool** [ReadBoolean](./readboolean/)() | 入力ストリームから単一のバイトを読み取り、そのブール表現を返します。 |
| virtual **uint8_t** [ReadByte](./readbyte/)() | 入力ストリームから単一のバイトを読み取ります。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | 入力ストリームから指定されたバイト数を読み取ります。 |
| virtual char_t [ReadChar](./readchar/)() | 入力ストリームから単一の文字を読み取ります。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | 入力ストリームから指定された文字数を読み取り、UTF-16 エンコーディングで返します。 |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | 実装されていません。 |
| virtual **double** [ReadDouble](./readdouble/)() | 入力ストリームから 8 バイトを読み取り、倍精度浮動小数点値として返します。 |
| virtual **int16_t** [ReadInt16](./readint16/)() | 入力ストリームから 2 バイトを読み取り、16 ビット整数値として返します。 |
| virtual int [ReadInt32](./readint32/)() | 入力ストリームから 4 バイトを読み取り、32 ビット整数値として返します。 |
| virtual **int64_t** [ReadInt64](./readint64/)() | 入力ストリームから 8 バイトを読み取り、64 ビット整数値として返します。 |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | 入力ストリームから単一のバイトを読み取り、符号付き 8 ビット整数値として返します。 |
| virtual **float** [ReadSingle](./readsingle/)() | 入力ストリームから 4 バイトを読み取り、単精度浮動小数点値として返します。 |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | 現在のストリームから文字列を読み取ります。文字列は長さが前置され、整数を 7 ビットずつエンコードした形です。 |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | 入力ストリームから 2 バイトを読み取り、符号なし 16 ビット整数値として返します。 |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | 入力ストリームから 4 バイトを読み取り、符号なし 32 ビット整数値として返します。 |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | 入力ストリームから 8 バイトを読み取り、符号なし 64 ビット整数値として返します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) 監視オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~BinaryReader](./~binaryreader/)() | デストラクタ。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破壊します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IDisposable](../../system/idisposable/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)