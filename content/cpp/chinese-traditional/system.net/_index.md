---
title: "System::Net"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 651
url: /zh-hant/system.net/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [Cookie](./cookie/) | 代表 HTTP Cookie。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [CookieCollection](./cookiecollection/) | 代表已排序的 Cookie 列表。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [CookieComparer](./cookiecomparer/) | 用於比較 [Cookie](./cookie/) 類別實例。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [CookieContainer](./cookiecontainer/) | 提供 CookieCollection 類別實例的容器。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [CookieParser](./cookieparser/) | 用於解析 cookie 標頭並建立 [Cookie](./cookie/) 類別的實例。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [CredentialCache](./credentialcache/) | 提供憑證儲存。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Details_CookieException](./details_cookieexception/) | 代表在 [CookieContainer](./cookiecontainer/) 大小超過 MaxCookieSize 屬性值時拋出的例外。切勿手動建立此類別實例，請改用 CookieException 類別。切勿將 CookieException 類別實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [Details_WebException](./details_webexception/) | 代表 [WebRequest](./webrequest/) 在發生錯誤時拋出的例外。切勿手動建立此類別實例，請改用 WebException 類別。切勿將 WebException 類別實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [Dns](./dns/) | 提供用於 DNS 的方法。 |
| [DnsEndPoint](./dnsendpoint/) | 包含應用程式連接服務所需的資訊。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [EndPoint](./endpoint/) | 抽象類別，包含網路位址。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [FileWebRequest](./filewebrequest/) | 提供 [WebRequest](./webrequest/) 抽象類別在檔案系統上的實作。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [FileWebResponse](./filewebresponse/) | 提供 [WebResponse](./webresponse/) 抽象類別在檔案系統上的實作。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [FtpWebRequest](./ftpwebrequest/) | 實作檔案傳輸協定 (FTP) 用戶端的虛擬類別。此類僅用於讓已翻譯的程式碼能與 [FtpWebRequest](./ftpwebrequest/) 參考連結，並不執行任何功能，且未實作任何成員。 |
| [FtpWebResponse](./ftpwebresponse/) | 虛擬類別，使已翻譯的程式碼能與 [FtpWebResponse](./ftpwebresponse/) 參考連結，並不執行任何功能，且未實作任何成員。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [HeaderVariantInfo](./headervariantinfo/) | 用於比對 cookie 名稱與規範。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [HttpKnownHeaderNames](./httpknownheadernames/) | 包含已知標頭名稱的字串值。 |
| [HttpRequestHeaderExtensions](./httprequestheaderextensions/) | 包含用於處理 HttpRequestHeader 列舉值的工具方法。 |
| [HttpResponseHeaderExtensions](./httpresponseheaderextensions/) | 包含用於處理 HttpResponseHeader 列舉值的工具方法。 |
| [HttpStatusDescription](./httpstatusdescription/) | 包含取得 HTTP 狀態字串表示的工具方法。 |
| [HttpVersion](./httpversion/) | 包含 HTTP 版本。 |
| [HttpWebRequest](./httpwebrequest/) | 代表 HTTP 網路請求。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [HttpWebResponse](./httpwebresponse/) | 代表 HTTP 網路回應。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ICredentials](./icredentials/) | 提供驗證介面。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ICredentialsByHost](./icredentialsbyhost/) | 提供取得主機、埠號與驗證類型之憑證的驗證介面。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IPAddress](./ipaddress/) | 代表 IP 位址。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IPEndPoint](./ipendpoint/) | 代表包含 IP 位址與埠號的網路端點。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IPHostEntry](./iphostentry/) | 代表網際網路主機位址的相關資訊。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IWebProxy](./iwebproxy/) | 此介面用於實作對 [WebRequest](./webrequest/) 類別的代理存取。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IWebRequestCreate](./iwebrequestcreate/) | 提供建立 [WebRequest](./webrequest/) 類別實例的方法。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [NetworkCredential](./networkcredential/) | 提供基於密碼的驗證機制的憑證。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [PathList](./pathlist/) | 代表 [CookieCollection](./cookiecollection/) 類別實例的清單。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ServicePoint](./servicepoint/) | 提供 HTTP 連線管理。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ServicePointManager](./servicepointmanager/) | 管理 [ServicePoint](./servicepoint/) 類別實例的生命週期（建立、維護與刪除）。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SocketAddress](./socketaddress/) | 用於儲存 [EndPoint](./endpoint/) 類別實例的序列化資訊。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [UriScheme](./urischeme/) | 代表 URI 的方案。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [WebClient](./webclient/) | [WebClient](./webclient/) 提供傳送與接收資料的通用方法。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [WebHeaderCollection](./webheadercollection/) | 代表協定標頭的集合。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [WebProxy](./webproxy/) | 代表 HTTP 網路代理伺服器。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [WebRequest](./webrequest/) | 代表網路請求。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [WebRequestMethods](./webrequestmethods/) | 包含網路請求的字串常數。 |
| [WebResponse](./webresponse/) | 代表網路回應。此類的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
## 列舉

| 列舉 | 說明 |
| --- | --- |
| [AuthenticationSchemes](./authenticationschemes/) | 列舉驗證方案。 |
| [CookieVariant](./cookievariant/) | 列舉 cookie 規範。 |
| [DecompressionMethods](./decompressionmethods/) | 列舉壓縮/解壓縮演算法。 |
| [HttpRequestHeader](./httprequestheader/) | 列舉請求標頭。 |
| [HttpResponseHeader](./httpresponseheader/) | 列舉 HTTP 回應標頭。 |
| [HttpStatusCode](./httpstatuscode/) |  |
| [SecurityProtocolType](./securityprotocoltype/) | 列舉安全協定類型。 |
| [TransportType](./transporttype/) | 定義套接字允許的傳輸類型。 |
| [WebExceptionStatus](./webexceptionstatus/) | 列舉 WebException 類別的狀態碼。 |
| [WebHeaderCollectionType](./webheadercollectiontype/) | 列舉協定標頭集合的類型。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [CookieException](./cookieexception/) |  |
| [BindIPEndPoint](./bindipendpoint/) |  |
| [WebException](./webexception/) |  |