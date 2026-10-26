---
title: HttpWebRequest
second_title: Aspose.Slides for C++ API Referansı
description: "HTTP web isteğini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde veya new operatörü ile asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 274
url: /tr/system.net/httpwebrequest/
---
## HttpWebRequest sınıfı

HTTP web isteğini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde veya new operatörü ile asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Abort](./abort/)() override | Geçerli isteği iptal eder. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Geçerli isteğe '[Range](../../system/range/)' başlığını ekler. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Geçerli isteğe '[Range](../../system/range/)' başlığını ekler. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Kaynağa veri yazmak için bir akış almayı sağlayan asenkron bir işlemi başlatır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Kaynak için asenkron bir istek başlatır. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Belirtilen URI kullanılarak [WebRequest](../webrequest/) sınıfının yeni bir örneğini oluşturur. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Belirtilen URI kullanılarak [WebRequest](../webrequest/) sınıfının yeni bir örneğini oluşturur. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Belirtilen URI şeması için bir [WebRequest](../webrequest/) türevi oluşturur. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Belirtilen URI kullanılarak [WebRequest](../webrequest/) sınıfının yeni bir örneğini oluşturur. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Belirtilen URI kullanılarak [WebRequest](../webrequest/) sınıfının yeni bir örneğini oluşturur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Belirtilen akış alma asenkron işlemi tamamlanana kadar bekler. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Kaynak için belirtilen asenkron isteğin tamamlanmasını bekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Yalnızca dahili amaçlar için. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | ‘Accept’ HTTP başlığının değerini alır. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | İsteğin yönlendirmeleri izlemesi gerektiğini gösteren bir değer alır. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Kaynağın gönderdiği verinin tamponlanması gerekip gerekmediğini gösteren bir değer alır. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Veri gönderimi için tamponlamanın etkin olup olmadığını gösteren bir değer alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Önbellek politikasını alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Geçerli istek ile ilişkili sertifikaların koleksiyonunu alır. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Bağlantı grubunun adını alır. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Gönderilecek istek verisinin bayt sayısını alır. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | İsteğin MIME tipini alır. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | 100-Continue durum kodu alınana kadar bekleyecek zaman aşımını alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Geçerli web isteğiyle ilişkili bir çerez kapsayıcısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Geçerli istek ile ilişkili kimlik doğrulama bilgisini alır. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Genel HTTP proxy'sini alır. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Bir yanıt alınıp alınmadığını gösteren bir değer döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | HTTP başlıklarının koleksiyonunu alır. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Geçerli isteğin 'Keep-Alive' başlığı içerip içermediğini gösteren bir değer alır. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | İzin verilen maksimum yönlendirme sayısını alır. |
| [String](../../system/string/) [get_Method](./get_method/)() override | HTTP yöntemini alır. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | İsteğin önceden kimlik doğrulaması yapılması gerekip gerekmediğini gösteren bir değer alır. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Ön ek listesini alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | HTTP proxy'sini alır. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | ‘Referer’ başlığının değerini alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | İstek URI'sını döndürür. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Verinin segmentler halinde gönderilip gönderilmemesi gerektiğini gösteren bir değer alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Kaynağa ağ bağlantısını temsil eden bir hizmet noktasını döndürür. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Geçerli isteğin bir çerez kapsayıcı kullanıp kullanamayacağını gösteren bir değer döndürür. |
| **int32_t** [get_Timeout](./get_timeout/)() override | İsteğin zaman aşımına uğrayacağı milisaniye cinsinden süreyi alır. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | ‘Credential’ özelliğinin ‘DefaultCredentials’ özelliğine eşit olup olmadığını gösteren bir değer alır. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | ‘User-Agent’ başlığının değerini alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogu. Özelleştirilmiş nesnelerin hashlenmesini sağlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Kaynağa veri yazmak için akışı döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Geçerli web isteğiyle ilişkili web yanıtını döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Yeni bir örnek oluşturur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özelleştirilmiş tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleşmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleşmesi. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Belirtilen URI için [WebRequest](../webrequest/) türevi kaydeder. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | ‘Accept’ HTTP başlığının değerini ayarlar. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | İsteğin yönlendirmeleri izlemesi gerektiğini gösteren bir değeri ayarlar. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Kaynağın gönderdiği verinin tamponlanması gerekip gerekmediğini gösteren bir değeri ayarlar. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Veri gönderimi için tamponlamanın etkin olup olmadığını gösteren bir değeri ayarlar. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Önbellek politikasını ayarlar. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Geçerli istek ile ilişkili sertifikaların koleksiyonunu ayarlar. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Bağlantı grubunun adını ayarlar. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Gönderilecek istek verisinin bayt sayısını ayarlar. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | İsteğin MIME tipini ayarlar. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | 100-Continue durum kodu alınana kadar bekleyecek zaman aşımını ayarlar. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Geçerli web isteğiyle ilişkili bir çerez kapsayıcısını ayarlar. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Geçerli istek ile ilişkili kimlik doğrulama bilgisini ayarlar. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Genel HTTP proxy'sini ayarlar. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | HTTP başlıklarının koleksiyonunu ayarlar. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Geçerli isteğin ‘Keep-Alive’ başlığını içerip içermediğini gösteren bir değeri ayarlar. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | İzin verilen maksimum yönlendirme sayısını ayarlar. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | HTTP yöntemini ayarlar. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | İsteğin önceden kimlik doğrulaması yapılması gerektiğini gösteren bir değeri ayarlar. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Ön ek listesini ayarlar. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | HTTP sürümünü ayarlar. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | HTTP proxy'sini ayarlar. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | ‘Referer’ başlığının değerini ayarlar. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Verinin segmentler halinde gönderilmesi gerektiğini gösteren bir değeri ayarlar. |
| void [set_Timeout](./set_timeout/)(int) override | İsteğin zaman aşımına uğrayacağı milisaniye cinsinden süreyi ayarlar. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | İsteğin zaman aşımına uğrayacağı milisaniye cinsinden süreyi ayarlar. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | ‘Credential’ özelliğinin ‘DefaultCredentials’ özelliğine eşit olup olmadığını gösteren bir değeri ayarlar. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | ‘User-Agent’ başlığının değerini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı değil zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişi sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özelleştirilmiş nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [WebRequest](../webrequest/)
* Ad alanı [System::Net](../)
* Kütüphane [Aspose.Slides](../../)