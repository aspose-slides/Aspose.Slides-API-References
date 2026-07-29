---
title: HttpWebRequest
second_title: Aspose.Slides för C++ API-referens
description: "Representerar HTTP-webbförfrågan. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 274
url: /sv/system.net/httpwebrequest/
---
## HttpWebRequest klass


Representerar HTTP-webbförfrågan. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Abort](./abort/)() override | Avbryter den aktuella förfrågan. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Lägger till '[Range](../../system/range/)'-huvudet till den aktuella förfrågan. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Lägger till '[Range](../../system/range/)'-huvudet till den aktuella förfrågan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inleder en asynkron operation för att få en ström för att skriva data till resursen. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inleder en asynkron begäran för resursen. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Skapar en ny instans av [WebRequest](../webrequest/)-klassen med den angivna URI:n. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Skapar en ny instans av [WebRequest](../webrequest/)-klassen med den angivna URI:n. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Skapar en [WebRequest](../webrequest/)-nedärvd för det angivna URI-schemat. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Skapar en ny instans av [WebRequest](../webrequest/)-klassen med den angivna URI:n. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Skapar en ny instans av [WebRequest](../webrequest/)-klassen med den angivna URI:n. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Väntar tills den angivna asynkrona operationen för att få en ström är klar. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Väntar tills den angivna asynkrona begäran för resursen är klar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Hämtar värdet för 'Accept'-HTTP-huvudet. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Hämtar ett värde som indikerar om förfrågan ska följa omdirigeringar. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Hämtar ett värde som indikerar om data som tas emot från resursen måste buffras. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Hämtar ett värde som indikerar om buffring är aktiverad för att skicka data. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Hämtar cachepolicyn. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Hämtar samlingen av certifikat som är associerade med den aktuella förfrågan. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Hämtar namnet på anslutningsgruppen. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Hämtar antalet byte av förfrågningsdata som ska skickas. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Hämtar MIME-typen för förfrågan. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Hämtar en timeout att vänta tills 100-Continue-statuskoden mottas. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Hämtar en cookiebehållare associerad med den aktuella webbförfrågan. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Hämtar autentiseringsinformation som är associerad med den aktuella förfrågan. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Hämtar den globala HTTP-proxyn. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Returnerar ett värde som indikerar om ett svar har mottagits. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Hämtar samlingen av HTTP-huvuden. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Hämtar ett värde som indikerar om den aktuella förfrågan måste innehålla 'Keep-Alive'-huvudet. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Hämtar maxantalet tillåtna omdirigeringar. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Hämtar HTTP-metoden. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Hämtar ett värde som indikerar om förfrågan måste förautentiseras. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Hämtar prefixlistan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Hämtar HTTP-proxyn. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Hämtar värdet av 'Referer'-huvudet. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Returnerar förfrågnings-URI:n. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Hämtar ett värde som indikerar om data måste skickas i segment. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Returnerar en servicepunkt som representerar nätverksanslutningen till resursen. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Returnerar ett värde som indikerar om den aktuella förfrågan kan använda en cookiebehållare. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Hämtar en tidsmängd i millisekunder efter vilken förfrågan får timeout. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Hämtar ett värde som indikerar om 'Credential'-egenskapen är lika med 'DefaultCredentials'-egenskapen. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Hämtar värdet av 'User-Agent'-huvudet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Gör det möjligt att hash-a anpassade objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Returnerar strömmen för att skriva data till resursen. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Returnerar webbsvaret som är associerat med den aktuella webbförfrågan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Konstrukterar en ny instans. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Registrerar [WebRequest](../webrequest/)-nedärvd för den angivna URI:n. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknandet med angivet värde. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Ställer in värdet för 'Accept'-HTTP-huvudet. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Ställer in ett värde som indikerar om förfrågan ska följa omdirigeringar. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Ställer in ett värde som indikerar om data som tas emot från resursen måste buffras. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Ställer in ett värde som indikerar om buffring är aktiverad för att skicka data. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Ställer in cachepolicyn. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Ställer in samlingen av certifikat som är associerade med den aktuella förfrågan. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Ställer in namnet på anslutningsgruppen. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Ställer in antalet byte av förfrågningsdata som ska skickas. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Ställer in MIME-typen för förfrågan. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Ställer in en timeout att vänta tills 100-Continue-statuskoden mottas. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Ställer in en cookiebehållare som är associerad med den aktuella webbförfrågan. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Ställer in autentiseringsinformation som är associerad med den aktuella förfrågan. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Ställer in den globala HTTP-proxyn. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Ställer in samlingen av HTTP-huvuden. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Ställer in ett värde som indikerar om den aktuella förfrågan måste innehålla 'Keep-Alive'-huvudet. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Ställer in maximalt tillåtet antal omdirigeringar. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Ställer in HTTP-metoden. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Ställer in ett värde som indikerar om förfrågan måste förautentiseras. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Ställer in prefixlistan. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Ställer in HTTP-versionen. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Ställer in HTTP-proxyn. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Ställer in ett värde för 'Referer'-huvudet. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Ställer in ett värde som indikerar om data måste skickas i segment. |
| void [set_Timeout](./set_timeout/)(int) override | Ställer in en tidsmängd i millisekunder efter vilken förfrågan får timeout. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Ställer in en tidsmängd i millisekunder efter vilken förfrågan får timeout. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Ställer in ett värde som indikerar om 'Credential'-egenskapen är lika med 'DefaultCredentials'-egenskapen. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Ställer in ett värde för 'User-Agent'-huvudet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i container till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar det delade referensräknandet. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar det delade referensräknandet. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svagt referensräknande. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svagt referensräknande. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [WebRequest](../webrequest/)
* Namnrymd [System::Net](../)
* Bibliotek [Aspose.Slides](../../)