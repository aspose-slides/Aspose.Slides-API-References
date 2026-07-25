---
title: HttpWebResponse
second_title: Aspose.Slides for C++ API リファレンス
description: "HTTP Web 応答を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション障害の原因となります。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数に引数として渡してください。"
type: docs
weight: 287
url: /ja/system.net/httpwebresponse/
---
## HttpWebResponse クラス


HTTP Web 応答を表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してインスタンスを作成しないでください。実行時エラーやアサーション障害の原因となります。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。

```cpp
class HttpWebResponse : public System::Net::WebResponse
```

## メソッド

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | 応答ストリームを閉じます。 |
| void [Dispose](../webresponse/dispose/)() override | 何もしません。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| [System::String](../../system/string/) [get_CharacterSet](./get_characterset/)() | 未実装です。 |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | リソースのバイト数を返します。 |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | リソースの MIME タイプを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [get_Cookies](./get_cookies/)() | Web 応答に関連付けられたクッキーを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | 現在の応答に関連付けられたヘッダーのコレクションを返します。 |
| virtual [String](../../system/string/) [get_Method](./get_method/)() | HTTP メソッドを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_ResponseUri](./get_responseuri/)() override | リソースの URI を返します。 |
| virtual [HttpStatusCode](../httpstatuscode/) [get_StatusCode](./get_statuscode/)() | Web 応答に関連付けられた HTTP ステータスコードを返します。 |
| virtual [String](../../system/string/) [get_StatusDescription](./get_statusdescription/)() | ステータスコードの文字列表現を返します。 |
| **bool** [get_SupportsHeaders](./get_supportsheaders/)() override | 現在の応答がヘッダーをサポートしているかどうかを示す値を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| [String](../../system/string/) [GetResponseHeader](./getresponseheader/)([String](../../system/string/)) | 指定されたヘッダー名に対応する値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [GetResponseStream](./getresponsestream/)() override | 応答ストリームを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
|  [HttpWebResponse](./httpwebresponse/)([System::SharedPtr](../../system/sharedptr/)\<[Http::HttpResponseMessage](../../system.net.http/httpresponsemessage/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[CookieContainer](../cookiecontainer/)\>) | 新しいインスタンスを構築します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [WebResponse](../webresponse/)
* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)