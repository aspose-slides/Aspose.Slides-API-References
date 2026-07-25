---
title: HttpWebRequest
second_title: Aspose.Slides for C++ API リファレンス
description: "HTTP Web リクエストを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 274
url: /ja/system.net/httpwebrequest/
---
## HttpWebRequest クラス

HTTP Web リクエストを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Abort](./abort/)() override | 現在のリクエストを中止します。 |
| virtual void [AddRange](./addrange/)(**int32_t**) | 現在のリクエストに '[Range](../../system/range/)' ヘッダーを追加します。 |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | 現在のリクエストに '[Range](../../system/range/)' ヘッダーを追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | リソースへデータを書き込むためのストリームを取得する非同期操作を開始します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | リソースに対する非同期リクエストを開始します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | 指定された URI を使用して [WebRequest](../webrequest/) クラスの新しいインスタンスを作成します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 指定された URI を使用して [WebRequest](../webrequest/) クラスの新しいインスタンスを作成します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 指定された URI スキームに対する [WebRequest](../webrequest/) の子クラスを作成します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | 指定された URI を使用して [WebRequest](../webrequest/) クラスの新しいインスタンスを作成します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 指定された URI を使用して [WebRequest](../webrequest/) クラスの新しいインスタンスを作成します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 指定されたストリーム取得非同期操作が完了するまで待機します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 指定されたリソースに対する非同期リクエストが完了するまで待機します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを用いてオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [String](../../system/string/) [get_Accept](./get_accept/)() | 'Accept' HTTP ヘッダーの値を取得します。 |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | リクエストがリダイレクトに従うかどうかを示す値を取得します。 |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | リソースから受信したデータをバッファリングする必要があるかどうかを示す値を取得します。 |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | データ送信時にバッファリングが有効かどうかを示す値を取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | キャッシュポリシーを取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | 現在のリクエストに関連付けられた証明書のコレクションを取得します。 |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | 接続グループの名前を取得します。 |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | 送信されるリクエストデータのバイト数を取得します。 |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | リクエストの MIME タイプを取得します。 |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | 100-Continue ステータスコードが受信されるまで待機するタイムアウトを取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | 現在の Web リクエストに関連付けられたクッキーコンテナを取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | 現在のリクエストに関連付けられた認証情報を取得します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | グローバル HTTP プロキシを取得します。 |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | レスポンスが受信されたかどうかを示す値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | HTTP ヘッダーのコレクションを取得します。 |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | 現在のリクエストが 'Keep-Alive' ヘッダーを含む必要があるかどうかを示す値を取得します。 |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | 許可されるリダイレクトの最大数を取得します。 |
| [String](../../system/string/) [get_Method](./get_method/)() override | HTTP メソッドを取得します。 |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | リクエストが事前認証である必要があるかどうかを示す値を取得します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | プレフィックスリストを取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | HTTP プロキシを取得します。 |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | 'Referer' ヘッダーの値を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | リクエスト URI を返します。 |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | データを分割して送信する必要があるかどうかを示す値を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | リソースへのネットワーク接続を表すサービスポイントを返します。 |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | 現在のリクエストがクッキーコンテナを使用できるかどうかを示す値を返します。 |
| **int32_t** [get_Timeout](./get_timeout/)() override | リクエストがタイムアウトになるまでのミリ秒単位の時間を取得します。 |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | 'Credential' プロパティが 'DefaultCredentials' プロパティと等しいかどうかを示す値を取得します。 |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | 'User-Agent' ヘッダーの値を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | リソースへデータを書き込むためのストリームを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | 現在の Web リクエストに関連付けられた Web レスポンスを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 新しいインスタンスを構築します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | 指定された URI に対して [WebRequest](../webrequest/) の子クラスを登録します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | 'Accept' HTTP ヘッダーの値を設定します。 |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | リクエストがリダイレクトに従うかどうかを示す値を設定します。 |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | リソースから受信したデータをバッファリングする必要があるかどうかを示す値を設定します。 |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | データ送信時にバッファリングが有効かどうかを示す値を設定します。 |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | キャッシュポリシーを設定します。 |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | 現在のリクエストに関連付けられた証明書のコレクションを設定します。 |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | 接続グループの名前を設定します。 |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | 送信するリクエストデータのバイト数を設定します。 |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | リクエストの MIME タイプを設定します。 |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | 100-Continue ステータスコードが受信されるまで待機するタイムアウトを設定します。 |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | 現在の Web リクエストに関連付けられたクッキーコンテナを設定します。 |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | 現在のリクエストに関連付けられた認証情報を設定します。 |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | グローバル HTTP プロキシを設定します。 |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | HTTP ヘッダーのコレクションを設定します。 |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | 現在のリクエストが 'Keep-Alive' ヘッダーを含む必要があるかどうかを示す値を設定します。 |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | 許可されるリダイレクトの最大数を設定します。 |
| void [set_Method](./set_method/)([String](../../system/string/)) override | HTTP メソッドを設定します。 |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | リクエストが事前認証である必要があるかどうかを示す値を設定します。 |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | プレフィックスリストを設定します。 |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | HTTP のバージョンを設定します。 |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | HTTP プロキシを設定します。 |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | 'Referer' ヘッダーの値を設定します。 |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | データを分割して送信する必要があるかどうかを示す値を設定します。 |
| void [set_Timeout](./set_timeout/)(int) override | リクエストがタイムアウトになるまでのミリ秒単位の時間を設定します。 |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | リクエストがタイムアウトになるまでのミリ秒単位の時間を設定します。 |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | 'Credential' プロパティが 'DefaultCredentials' プロパティと等しいかどうかを示す値を設定します。 |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | 'User-Agent' ヘッダーの値を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth テンプレート引数を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [WebRequest](../webrequest/)
* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)