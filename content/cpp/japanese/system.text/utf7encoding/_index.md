---
title: UTF7Encoding
second_title: Aspose.Slides for C++ API リファレンス
description: "UTF-7 エンコーディング。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡して使用してください。"
type: docs
weight: 365
url: /ja/system.text/utf7encoding/
---
## UTF7Encoding クラス

UTF-7 エンコーディング。 このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | エンコーディングオブジェクトのクローンを作成します。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 2 つのエンコーディング間でバイトを変換します。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 2 つのエンコーディング間でバイトを変換します。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | オブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 自身を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 自身を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII エンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | 標準的なビッグエンディアン Unicode エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | 標準的なビッグエンディアン UTF-32 エンコーディングオブジェクトを取得します。 |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | メールエージェントの本文互換エンコーディング名を取得します。 |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) のコードページ ID を取得します。 |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | デコーダのフォールバックを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | デフォルトエンコーディングを取得します。 |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | エンコーダのフォールバックを取得します。 |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | 人間が読みやすいエンコーディング名を取得します。 |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | メールエージェントのヘッダー互換エンコーディング名を取得します。 |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | エンコーディングがブラウザーでコンテンツを表示するのに使用できるかを確認します。 |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | エンコーディングがブラウザーでコンテンツを保存するのに使用できるかを確認します。 |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | エンコーディングがメールクライアントでコンテンツを表示するのに使用できるかを確認します。 |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | エンコーディングがメールクライアントでコンテンツを保存するのに使用できるかを確認します。 |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | エンコーディングが読み取り専用かどうかを確認します。 |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | エンコーディングがシングルバイトかどうかを確認します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 エンコーディングを取得します。内部使用専用です。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | 標準的な Unicode エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | 標準的な UTF-7 エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | 標準的な UTF-8 エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | 内部専用で、クラス ライブラリが使用します：マークなしかつ入力検証なし。 |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA 互換エンコーディング名を取得します。 |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) のコードページ ID を取得します。 |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | 文字バッファをエンコードするのに必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 文字バッファをエンコードするのに必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | 文字バッファをエンコードするのに必要な文字数を取得します。 |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 文字バッファをエンコードするのに必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | 文字列をエンコードするのに必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 文字列をエンコードするのに必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | 文字バッファをエンコードするのに必要な文字数を取得します。 |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | 文字バッファをエンコードした結果のバイトを取得します。 |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | 文字バッファをエンコードした結果のバイトを取得します。 |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | 文字バッファをエンコードした結果のバイトを取得します。 |
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
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | バイトバッファをデコードするのに必要な文字数を取得します。 |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | バイトバッファをデコードするのに必要な文字数を取得します。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファをデコードするのに必要な文字数を取得します。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファをデコードするのに必要な文字数を取得します。 |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | バイトバッファをデコードするのに必要な文字数を取得します。 |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | バイトバッファをデコードした結果得られる文字を取得します。 |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | バイトバッファをデコードした結果得られる文字を取得します。 |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | バイトバッファをデコードした結果得られる文字を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファをデコードした結果得られる文字を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファをデコードした結果得られる文字を取得します。 |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | バイトバッファをデコードした結果得られる文字を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | このオブジェクトに要求を転送するデコーダを取得します。 |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | このオブジェクトに要求を転送するエンコーダを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | 名前でエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | コードページでエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | コードページでエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 名前でエンコーディングを取得します。 |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | 既知のエンコーディングのリストを取得します。 |
| int [GetHashCode](./gethashcode/)() const override | エンコーディングのハッシュコードを取得します。 |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | 指定された文字数をエンコードするのに必要な最大バイト数を取得します。 |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | 指定されたバイト数をデコードするのに必要な最大文字数を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | エンコーディングを示すバイト列（例：BOM）を返します。 |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | バイトバッファを文字列にデコードします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しに相当します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子に相当します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | エンコーディングのパラメータを比較します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | デコーダのフォールバックを設定します。 |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | エンコーダのフォールバックを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドに相当します。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
|  [UTF7Encoding](./utf7encoding/)() | コンストラクタ。 |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | コンストラクタ。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | デフォルトコードページ値。 |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | [Windows](../../system.windows/) が UTF-7 コードページ ID 用に使用するマジックナンバー。 |

## 関連項目

* クラス [Encoding](../encoding/)
* 名前空間 [System::Text](../)
* ライブラリ [Aspose.Slides](../../)