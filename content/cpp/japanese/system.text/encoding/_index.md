---
title: Encoding
second_title: Aspose.Slides for C++ API リファレンス
description: エンコーディングサービス。
type: docs
weight: 222
url: /ja/system.text/encoding/
---
## エンコーディング クラス

[Encoding](./) サービス。

```cpp
class Encoding : public System::Object
```

## メソッド

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | エンコーディングオブジェクトをクローンします。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | バイトを 2 つのエンコーディング間で変換します。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | バイトを 2 つのエンコーディング間で変換します。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | エンコーディングを比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされる C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされる C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | ASCII エンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | 標準のビッグエンディアン Unicode エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | 標準のビッグエンディアン UTF-32 エンコーディングオブジェクトを取得します。 |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | メールエージェントの本文互換エンコーディング名を取得します。 |
| virtual int [get_CodePage](./get_codepage/)() | [Windows](../../system.windows/) コードページ ID を取得します。 |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | デコーダのフォールバックを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | デフォルトのエンコーディングを取得します。 |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | エンコーダのフォールバックを取得します。 |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | 人間が読めるエンコーディング名を取得します。 |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | メールエージェントのヘッダー互換エンコーディング名を取得します。 |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | エンコーディングがブラウザーでコンテンツを表示するために使用できるか確認します。 |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | エンコーディングがブラウザーでコンテンツを保存するために使用できるか確認します。 |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | エンコーディングがメールクライアントでコンテンツを表示するために使用できるか確認します。 |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | エンコーディングがメールクライアントでコンテンツを保存するために使用できるか確認します。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | エンコーディングが読み取り専用かどうか確認します。 |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | エンコーディングがシングルバイトかどうか確認します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Latin1 エンコーディングを取得します。内部使用のみ。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | 標準の Unicode エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | 標準の UTF-7 エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | 標準の UTF-8 エンコーディングオブジェクトを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | 内部専用で、クラス ライブラリで使用されます: 未マークおよび入力検証なし。 |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | IANA 互換エンコーディング名を取得します。 |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | [Windows](../../system.windows/) コードページ ID を取得します。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 文字バッファをエンコードするために必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | 文字バッファをエンコードするために必要な文字数を取得します。 |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 文字バッファをエンコードするために必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | 文字列をエンコードするために必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 文字バッファをエンコードするために必要な文字数を取得します。 |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | 文字バッファをエンコードするために必要な文字数を取得します。 |
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
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファをデコードするために必要な文字数を取得します。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファをデコードするために必要な文字数を取得します。 |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | バイトバッファをデコードするために必要な文字数を取得します。 |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | バイトバッファをデコードした結果得られる文字を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファをデコードした結果得られる文字を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファをデコードした結果得られる文字を取得します。 |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | バイトバッファをデコードした結果得られる文字を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | このオブジェクトにリクエストを転送するデコーダを取得します。 |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | このオブジェクトにリクエストを転送するエンコーダを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | 名前でエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | コードページでエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | コードページでエンコーディングを取得します。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 名前でエンコーディングを取得します。 |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | 既知のエンコーディング一覧を取得します。 |
| int [GetHashCode](./gethashcode/)() const override | エンコーディングをハッシュします。 |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | 指定された文字数をエンコードするために必要な最大バイト数を取得します。 |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | 指定されたバイト数をデコードするために必要な最大文字数を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | エンコーディングを示すバイト列（例: BOM）を返します。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | バイトバッファを文字列にデコードします。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | バイトバッファを文字列にデコードします。 |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | バイトバッファを文字列にデコードします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうか確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネスオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローンを可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | デコーダのフォールバックを設定します。 |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | エンコーダのフォールバックを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネスオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウンタをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | デフォルトのコードページ値。 |

## 型定義

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Text](../)
* ライブラリ [Aspose.Slides](../../)