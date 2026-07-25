---
title: BinaryWriter
second_title: Aspose.Slides for C++ API リファレンス
description: "プリミティブ型の値をバイトストリームに書き込むライターを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として使用してください。"
type: docs
weight: 105
url: /ja/system.io/binarywriter/
---
## BinaryWriter クラス

プリミティブ型の値をバイトストリームに書き込むライターを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡すようにしてください。

```cpp
class BinaryWriter : public System::IDisposable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | [BinaryWriter](./) クラスのインスタンスを作成します。このクラスは指定されたエンコーディングを使用して、指定されたストリームにデータを書き込みます。 |
| void [Close](./close/)() | 現在の [BinaryWriter](./) オブジェクトと基になる出力ストリームを閉じます。 |
| void [Dispose](./dispose/)() override | 現在のオブジェクトが使用しているすべてのリソースを解放し、基になるストリームを閉じます。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| void [Flush](./flush/)() | 出力ストリームをフラッシュします。 |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | 出力ストリームを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の、文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の、文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | 現在のオブジェクトが表すストリームの位置を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [Write](./write/)(**uint8_t**) | 指定された符号なし 8 ビット整数値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 指定されたバイト配列から指定されたサブレンジのバイトを書き込み、出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | 指定された文字配列から指定されたサブレンジの UTF-16 文字を書き込み、出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(**bool**) | 出力ストリームに 1 バイトを書き込みます。**value** が true のときは 0、false のときは 1 を書き込みます。 |
| virtual void [Write](./write/)(char16_t) | 指定された 16 ビット幅の文字値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(**int16_t**) | 指定された 16 ビット整数値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(int) | 指定された 32 ビット整数値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(**int64_t**) | 指定された 64 ビット整数値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(**uint16_t**) | 指定された符号なし 16 ビット整数値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(**uint32_t**) | 指定された符号なし 32 ビット整数値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(**uint64_t**) | 指定された符号なし 64 ビット整数値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(**float**) | 指定された単精度浮動小数点値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(**double**) | 指定された倍精度浮動小数点値を出力ストリームに書き込みます。 |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | 指定された [Decimal](../../system/decimal/) 値のバイト表現を書き込みます。 |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | 現在のエンコーディングで長さプレフィックス付き文字列を書き込みます。 |
| virtual void [Write](./write/)(const char_t *) | 現在のエンコーディングで長さプレフィックス付き文字列を書き込みます。 |
|  [~BinaryWriter](./~binarywriter/)() | デストラクタです。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IDisposable](../../system/idisposable/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)