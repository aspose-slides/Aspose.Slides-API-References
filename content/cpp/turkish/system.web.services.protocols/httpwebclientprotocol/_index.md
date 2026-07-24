---
title: HttpWebClientProtocol
second_title: Aspose.Slides for C++ API Referansı
description: "Bu temel sınıf, HTTP kullanan tüm XML Web hizmet istemci vekillerinde kullanılır. Bu sınıfa ait nesneler yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü bunun sonucunda çalışma zamanı hataları ve/veya doğrulama hataları oluşur. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin."
type: docs
weight: 14
url: /tr/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol sınıf

Bu temel sınıf, HTTP kullanan tüm XML [Web](../../system.web/) hizmet istemci vekillerinde kullanılır. Bu sınıfa ait nesneler yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü bunun sonucunda çalışma zamanı hataları ve/veya doğrulama hataları oluşur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Metotlar

| Method | Description |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | İsteği iptal eder. |
| virtual void [CheckForCookies](./checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Belirtilen istekteki çerezleri dahili çerez saklayıcısına ekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) sözdizimiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesnelerini C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesnelerini C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | İstemcinin sunucu yönlendirmelerini takip edip etmediğini gösteren bir değer alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | İstemci sertifikalarının koleksiyonunu döndürür. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Bağlantı grubunun adını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Çerezleri depolamak için kullanılan bir konteyner alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Kimlik doğrulama bilgilerini alır. |
| **bool** [get_EnableDecompression](./get_enabledecompression/)() | Açmanın etkin olup olmadığını gösteren bir değer alır. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Ön kimlik doğrulamanın etkin olup olmadığını gösteren bir değer alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](./get_proxy/)() | Vekil (proxy) bilgilerini alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | İstemci isteklerini oluşturmak için kullanılan kodlamayı alır. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | İsteğin zaman aşımına uğramadan önce bekleyeceği süreyi alır. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | İstemci NTLM kimlik doğrulaması kullandığında bağlantı paylaşımının etkin olup olmadığını gösteren bir değer alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | XML [Web](../../system.web/) hizmetinin URI'sını alır. |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | XML [Web](../../system.web/) hizmetinin URL'sini alır. |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | ‘Credential’ özelliğinin ‘DefaultCredentials’ özelliğine eşit olup olmadığını gösteren bir değer alır. |
| [String](../../system/string/) [get_UserAgent](./get_useragent/)() | ‘User-Agent’ başlığının değerini alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını ilklendirir. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi ilklendirir ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi ilklendirir ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesi ile nullptr'ı referansla karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | İstemcinin sunucu yönlendirmelerini takip edip etmeyeceğini gösteren bir değer ayarlar. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Bağlantı grubunun adını ayarlar. |
| void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Çerezleri depolamak için kullanılan bir konteyner ayarlar. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Kimlik doğrulama bilgisini ayarlar. |
| void [set_EnableDecompression](./set_enabledecompression/)(**bool**) | Açmanın etkin olup olmadığını gösteren bir değer ayarlar. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Ön kimlik doğrulamanın etkin olup olmadığını gösteren bir değer ayarlar. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Vekil (proxy) bilgilerini ayarlar. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | İstemci isteklerini oluşturmak için kullanılan kodlamayı ayarlar. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | İsteğin zaman aşımına uğramadan önce bekleyeceği süreyi ayarlar. |
| void [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(**bool**) | İstemci NTLM kimlik doğrulaması kullandığında bağlantı paylaşımının etkin olup olmadığını gösteren bir değer ayarlar. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | XML [Web](../../system.web/) hizmetinin URI'sını ayarlar. |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | XML [Web](../../system.web/) hizmetinin URL'sini ayarlar. |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | ‘Credential’ özelliğinin ‘DefaultCredentials’ özelliğine eşit olup olmadığını gösteren bir değer ayarlar. |
| void [set_UserAgent](./set_useragent/)([String](../../system/string/)) | ‘User-Agent’ başlığının değerini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) ayarlar. Konteynerlerde işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| void [UnregisterMapping](./unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [WebClientProtocol](../webclientprotocol/)
* İsim alanı [System::Web::Services::Protocols](../)
* Kütüphane [Aspose.Slides](../../)