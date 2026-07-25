---
title: ICUEncoding
second_title: Aspose.Slides for C++ API リファレンス
description: "ICUベースのエンコーディング実装です。内部使用のみ。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 300
url: /ja/system.text/icuencoding/
---
## ICUEncoding クラス

ICU に基づくエンコーディング実装です。内部使用のみ。[System::MakeObject()](../../system/makeobject/) 関数を使用してのみこのクラスのオブジェクトを割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。

```cpp
class ICUEncoding : public System::Text::Encoding
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | エンコーディングオブジェクトを複製します。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 2 つのエンコーディング間でバイトを変換します。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 2 つのエンコーディング間でバイトを変換します。 |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | エンコーディングを比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部利用のみ。 |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII エンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | 標準のビッグエンディアン Unicode エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | 標準のビッグエンディアン UTF-32 エンコーディングオブジェクトを取得します。 |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | メールエージェントの本文に適合するエンコーディング名を取得します。 |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) コードページ ID を取得します。 |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | デコーダのフォールバックを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | デフォルトエンコーディングを取得します。 |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | エンコーダのフォールバックを取得します。 |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | 人間が読めるエンコーディング名を取得します。 |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | メールエージェントのヘッダーに適合するエンコーディング名を取得します。 |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | エンコーディングがブラウザーでコンテンツを表示するために使用できるかどうかを確認します。 |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | エンコーディングがブラウザーでコンテンツを保存するために使用できるかどうかを確認します。 |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | エンコーディングがメールクライアントでコンテンツを表示するために使用できるかどうかを確認します。 |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | エンコーディングがメールクライアントでコンテンツを保存するために使用できるかどうかを確認します。 |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | エンコーディングが読み取り専用かどうかを確認します。 |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | エンコーディングがシングルバイトかどうかを確認します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 エンコーディングを取得します。内部利用のみ。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | 標準の Unicode エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | 標準の UTF-7 エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | 標準の UTF-8 エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | 内部専用で、クラス ライブラリで使用するためのものです：マーキングなし、入力検証なし。 |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA 互換エンコーディング名を取得します。 |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) コードページ ID を取得します。 |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | 文字バッファをエンコードするのに必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI。 |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI。 |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI。 |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | RTTI。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI。 |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | RTTI。 |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | 文字バッファをエンコードした結果のバイトを取得します。 |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 文字バッファをエンコードした結果のバイトを取得します。 |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | 文字バッファをエンコードした結果のバイトを取得します。 |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | 文字バッファをエンコードした結果のバイトを取得します。 |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 文字バッファをエンコードした結果のバイトを取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | 文字バッファをエンコードした結果のバイトを取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 文字バッファをエンコードした結果のバイトを取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | 文字バッファをエンコードした結果のバイトを取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 文字バッファをエンコードした結果のバイトを取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 文字バッファをエンコードした結果のバイトを取得します。 |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | 文字バッファをエンコードした結果のバイトを取得します。 |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | バイトバッファをデコードするのに必要な文字数を取得します。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファをデコードするのに必要な文字数を取得します。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファをデコードするのに必要な文字数を取得します。 |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | バイトバッファをデコードするのに必要な文字数を取得します。 |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | バイトバッファをデコードした結果の文字を取得します。 |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | バイトバッファをデコードした結果の文字を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファをデコードした結果の文字を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファをデコードした結果の文字を取得します。 |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | バイトバッファをデコードした結果の文字を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | このオブジェクトへ要求を転送するデコーダを取得します。 |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | このオブジェクトへ要求を転送するエンコーダを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | 名前でエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | コードページでエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | コードページでエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 名前でエンコーディングを取得します。 |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | 既知のエンコーディングの一覧を取得します。 |
| int [GetHashCode](../encoding/gethashcode/)() const override | エンコーディングのハッシュを取得します。 |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | 指定された文字数をエンコードするのに必要な最大バイト数を取得します。 |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | 指定されたバイト数をデコードするのに必要な最大文字数を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | エンコーディングを示すバイト列（例：BOM）を返します。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | バイトバッファを文字列にデコードします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
|  [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | コンストラクタ。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子に相当します。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| **bool** [operator==](./operator_equal_equal/)(const [ICUEncoding](./)\&) const | コードページを使用してエンコーディングを比較します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | デコーダのフォールバックを設定します。 |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | エンコーダのフォールバックを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドに相当します。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | デフォルトのコードページ値。 |

## 参照

* クラス [Encoding](../encoding/)
* 名前空間 [System::Text](../)
* ライブラリ [Aspose.Slides](../../)