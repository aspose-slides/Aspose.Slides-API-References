---
title: StringWriter
second_title: Aspose.Slides for C++ API リファレンス
description: "文字列に情報を書き込む TextWriter を実装します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡して使用してください。"
type: docs
weight: 417
url: /ja/system.io/stringwriter/
---
## StringWriter クラス

Implements a [TextWriter](../textwriter/) that writes information to a string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | ストリームを閉じ、取得したリソースを解放します。 |
| void [Dispose](../textwriter/dispose/)() override | 現在のオブジェクトが使用しているすべてのリソースを解放し、基底ストリームを閉じます。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみで使用されます。 |
| virtual void [Flush](../textwriter/flush/)() | バッファの内容を基底ストリームにフラッシュします。 |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | 現在使用されているエンコーディングを返します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | 現在使用されている [IFormatProvider](../../system/iformatprovider/) オブジェクトを返します。 |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | 現在使用されている [IFormatProvider](../../system/iformatprovider/) オブジェクトを返します。 |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | 改行文字列を返します。 |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | 改行文字列を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | 現在使用されている StringBuilder を返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースの特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースの特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | 改行文字列を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 指定された StringBuilder と [IFormatProvider](../../system/iformatprovider/) を使用して [StringWriter](./) の新しいインスタンスを構築します。 |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 指定された StringBuilder と現在のカルチャーからの [IFormatProvider](../../system/iformatprovider/) を使用して [StringWriter](./) の新しいインスタンスを構築します。 |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 指定された [IFormatProvider](../../system/iformatprovider/) を使用して [StringWriter](./) の新しいインスタンスを構築します。 |
|  [StringWriter](./stringwriter/)() | 現在のカルチャーからの [IFormatProvider](../../system/iformatprovider/) を使用して [StringWriter](./) の新しいインスタンスを構築します。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 基底文字列を返します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Write](./write/)(char_t) override | 指定された文字をストリームに書き込みます。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 指定された文字配列から指定された文字サブレンジを書き込みます。 |
| void [Write](./write/)(const [String](../../system/string/)\&) override | 指定された文字列をストリームに書き込みます。 |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 指定されたオブジェクトの文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)(**bool**) | 指定されたブール値の文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | 指定された [Decimal](../../system/decimal/) オブジェクトの文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)(**double**) | 指定された倍精度浮動小数点値の文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)(int) | 指定された 32 ビット整数値の文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)(**int64_t**) | 指定された 64 ビット整数値の文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)(**float**) | 指定された単精度浮動小数点値の文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | 指定された符号なし 32 ビット整数値の文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | 指定された符号なし 64 ビット整数値の文字列表現を書き込みます。 |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 指定された配列のすべての文字を書き込みます。 |
| virtual void [Write](../textwriter/write/)(const char_t *) | 指定された C 文字列を書き込みます。 |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | 指定された [TypeInfo](../../system/typeinfo/) オブジェクトの文字列表現を書き込みます。 |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | 指定されたフォーマットに従って指定された値を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)() | 改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 指定されたオブジェクトの文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | 指定されたブール値の文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | 指定された文字を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | 指定された [Decimal](../../system/decimal/) オブジェクトの文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | 指定された倍精度浮動小数点値の文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(int) | 指定された 32 ビット整数値の文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | 指定された 64 ビット整数値の文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | 指定された単精度浮動小数点値の文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | 指定された文字列を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | 指定された符号なし 32 ビット整数値の文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | 指定された符号なし 64 ビット整数値の文字列表現を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 指定された配列のすべての文字を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 指定された文字配列から UTF-16 のサブレンジを書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | 指定された C 文字列を書き込み、続けて改行文字を書き込みます。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | 指定された [TypeInfo](../../system/typeinfo/) オブジェクトの文字列表現を書き込み、続けて改行文字を書き込みます。 |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 指定されたフォーマットに従って指定された値を書き込み、続けて改行文字を書き込みます。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | デストラクタです。 |

## 参照

* クラス [TextWriter](../textwriter/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)