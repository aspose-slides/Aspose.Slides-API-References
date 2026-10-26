---
title: HttpWebRequest
second_title: Aspose.Slides for C++ API 參考
description: "代表 HTTP 網路請求。此類別的物件應僅透過 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 274
url: /zh-hant/system.net/httpwebrequest/
---
## HttpWebRequest 類別


代表 HTTP 網路請求。此類的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [Abort](./abort/)() override | 中止目前的請求。 |
| virtual void [AddRange](./addrange/)(**int32_t**) | 將 '[Range](../../system/range/)' 標頭加入目前的請求。 |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | 將 '[Range](../../system/range/)' 標頭加入目前的請求。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 啟動非同步作業以取得用於寫入資料至資源的串流。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 啟動對資源的非同步請求。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | 使用指定的 URI 建立 [WebRequest](../webrequest/) 類別的新執行個體。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 使用指定的 URI 建立 [WebRequest](../webrequest/) 類別的新執行個體。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 為指定的 URI 方案建立 [WebRequest](../webrequest/) 的衍生類別。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | 使用指定的 URI 建立 [WebRequest](../webrequest/) 類別的新執行個體。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 使用指定的 URI 建立 [WebRequest](../webrequest/) 類別的新執行個體。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 等待指定的取得串流的非同步作業完成。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 等待指定的資源之非同步請求完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 以 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，於是即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，於是即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [String](../../system/string/) [get_Accept](./get_accept/)() | 取得 'Accept' HTTP 標頭的值。 |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | 取得指示是否應遵循重新導向之值。 |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | 取得指示是否必須緩衝從資源接收的資料之值。 |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | 取得指示傳送資料時是否已啟用緩衝之值。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | 取得快取原則。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | 取得與目前請求相關聯的憑證集合。 |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | 取得連線群組的名稱。 |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | 取得要傳送之請求資料的位元組數。 |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | 取得請求的 MIME 類型。 |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | 取得等待 100-Continue 狀態碼的逾時時間。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | 取得與目前網路請求相關聯的 Cookie 容器。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | 取得與目前請求相關聯的驗證資訊。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | 取得全域 HTTP 代理伺服器。 |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | 傳回指示是否已收到回應的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | 取得 HTTP 標頭的集合。 |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | 取得指示目前請求是否必須包含 'Keep-Alive' 標頭的值。 |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | 取得允許的最大重新導向次數。 |
| [String](../../system/string/) [get_Method](./get_method/)() override | 取得 HTTP 方法。 |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | 取得指示請求是否必須預先驗證的值。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | 取得前綴清單。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | 取得 HTTP 代理伺服器。 |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | 取得 'Referer' 標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | 傳回請求的 URI。 |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | 取得指示資料是否必須分段傳送的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | 傳回表示與資源之網路連線的服務點。 |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | 傳回指示目前請求是否可以使用 Cookie 容器的值。 |
| **int32_t** [get_Timeout](./get_timeout/)() override | 取得請求逾時前的毫秒時間。 |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | 取得指示 'Credential' 屬性是否等於 'DefaultCredentials' 屬性的值。 |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | 取得 'User-Agent' 標頭的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | 傳回寫入資料至資源的串流。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | 傳回與目前網路請求相關聯的網路回應。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 建構新執行個體。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 描述的型別實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | 為指定的 URI 註冊 [WebRequest](../webrequest/) 的衍生類別。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | 設定 'Accept' HTTP 標頭的值。 |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | 設定指示請求是否應遵循重新導向的值。 |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | 設定指示從資源接收的資料是否必須緩衝的值。 |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | 設定指示傳送資料時是否已啟用緩衝的值。 |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | 設定快取原則。 |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | 設定與目前請求相關聯的憑證集合。 |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | 設定連線群組的名稱。 |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | 設定要傳送之請求資料的位元組數。 |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | 設定請求的 MIME 類型。 |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | 設定等待 100-Continue 狀態碼的逾時時間。 |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | 設定與目前網路請求相關聯的 Cookie 容器。 |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | 設定與目前請求相關聯的驗證資訊。 |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | 設定全域 HTTP 代理伺服器。 |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | 設定 HTTP 標頭的集合。 |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | 設定指示目前請求必須包含 'Keep-Alive' 標頭的值。 |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | 設定允許的最大重新導向次數。 |
| void [set_Method](./set_method/)([String](../../system/string/)) override | 設定 HTTP 方法。 |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | 設定指示請求必須預先驗證的值。 |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | 設定前綴清單。 |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | 設定 HTTP 的版本。 |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | 設定 HTTP 代理伺服器。 |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | 設定 'Referer' 標頭的值。 |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | 設定指示資料是否必須分段傳送的值。 |
| void [set_Timeout](./set_timeout/)(int) override | 設定請求逾時前的毫秒時間。 |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | 設定請求逾時前的毫秒時間。 |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | 設定指示 'Credential' 屬性是否等於 'DefaultCredentials' 屬性的值。 |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | 設定 'User-Agent' 標頭的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前共享參考計數的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [WebRequest](../webrequest/)
* 命名空間 [System::Net](../)
* 函式庫 [Aspose.Slides](../../)