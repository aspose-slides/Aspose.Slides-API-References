---
title: HttpWebRequest
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de HTTP-webaanvraag voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime fouten en/of assertiefouten veroorzaakt. Wrap deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 274
url: /nl/system.net/httpwebrequest/
---
## HttpWebRequest klasse

Stelt de HTTP-webaanvraag voor. Objecten van deze klasse mogen alleen worden aangemaakt met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Abort](./abort/)() override | Annuleert het huidige verzoek. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Voegt de '[Range](../../system/range/)' header toe aan het huidige verzoek. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Voegt de '[Range](../../system/range/)' header toe aan het huidige verzoek. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Start een asynchrone bewerking om een stream te verkrijgen voor het schrijven van gegevens naar de bron. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Start een asynchrone aanvraag voor de bron. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Maakt een nieuw exemplaar van de [WebRequest](../webrequest/) klasse aan met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een nieuw exemplaar van de [WebRequest](../webrequest/) klasse aan met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een [WebRequest](../webrequest/) afstammeling voor het opgegeven URI-schema. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Maakt een nieuw exemplaar van de [WebRequest](../webrequest/) klasse aan met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een nieuw exemplaar van de [WebRequest](../webrequest/) klasse aan met de opgegeven URI. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Wacht tot de opgegeven asynchrone bewerking om een stream te verkrijgen is voltooid. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Wacht tot de opgegeven asynchrone aanvraag voor de bron is voltooid. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Haalt de 'Accept' HTTP-headerwaarde op. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Haalt een waarde op die aangeeft of het verzoek omleidingen moet volgen. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Haalt een waarde op die aangeeft of de gegevens ontvangen van de bron gebufferd moeten worden. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Haalt een waarde op die aangeeft of bufferen is ingeschakeld voor het verzenden van gegevens. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Haalt het cachebeleid op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Haalt de collectie van certificaten op die aan het huidige verzoek zijn gekoppeld. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Haalt de naam van de verbindingsgroep op. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Haalt het aantal bytes van de verzoekgegevens op die verzonden moeten worden. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Haalt het MIME-type van het verzoek op. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Haalt een time-out op om te wachten tot de 100-Continue-statuscode is ontvangen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Haalt een cookiecontainer op die aan het huidige webverzoek is gekoppeld. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Haalt authenticatie-informatie op die aan het huidige verzoek is gekoppeld. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Haalt de globale HTTP-proxy op. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Retourneert een waarde die aangeeft of een respons is ontvangen. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Haalt de collectie van de HTTP-headers op. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Haalt een waarde op die aangeeft of het huidige verzoek de 'Keep-Alive'-header moet bevatten. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Haalt het maximale aantal toegestane omleidingen op. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Haalt de HTTP-methode op. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Haalt een waarde op die aangeeft of het verzoek vooraf geauthenticeerd moet worden. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Haalt de prefixlijst op. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Haalt de HTTP-proxy op. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Haalt een waarde van de 'Referer'-header op. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Retourneert de verzoek-URI. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Haalt een waarde op die aangeeft of gegevens in segmenten moeten worden verzonden. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Retourneert een servicepunt dat de netwerkverbinding met de bron representeert. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Retourneert een waarde die aangeeft of het huidige verzoek een cookiecontainer kan gebruiken. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Haalt een tijdsduur in milliseconden op waarna het verzoek timet out. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Haalt een waarde op die aangeeft of de eigenschap 'Credential' gelijk is aan de eigenschap 'DefaultCredentials'. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Haalt een waarde van de 'User-Agent' header op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt hashing van aangepaste objecten in. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Retourneert de stream voor het schrijven van gegevens naar de bron. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Retourneert de webrespons die aan het huidige webverzoek is gekoppeld. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Construeert een nieuw exemplaar. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een exemplaar is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het C# lock()-statement voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt het klonen van aangepaste types in. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toekenningsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Registreert de [WebRequest](../webrequest/) afstammeling voor de opgegeven URI. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Stelt de 'Accept' HTTP-headerwaarde in. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Stelt een waarde in die aangeeft of het verzoek omleidingen moet volgen. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Stelt een waarde in die aangeeft of de gegevens ontvangen van de bron gebufferd moeten worden. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Stelt een waarde in die aangeeft of bufferen ingeschakeld is voor het verzenden van gegevens. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Stelt het cachebeleid in. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Stelt de collectie van certificaten in die aan het huidige verzoek zijn gekoppeld. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Stelt de naam van de verbindingsgroep in. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Stelt het aantal bytes van de verzoekgegevens in die verzonden moeten worden. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Stelt het MIME-type van het verzoek in. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Stelt een time-out in om te wachten tot de 100-Continue-statuscode is ontvangen. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Stelt een cookiecontainer in die aan het huidige webverzoek is gekoppeld. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Stelt authenticatie-informatie in die aan het huidige verzoek is gekoppeld. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Stelt de globale HTTP-proxy in. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Stelt de collectie van de HTTP-headers in. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Stelt een waarde in die aangeeft of het huidige verzoek de 'Keep-Alive'-header moet bevatten. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Stelt een maximaal aantal toegestane omleidingen in. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Stelt de HTTP-methode in. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Stelt een waarde in die aangeeft of het verzoek vooraf geauthenticeerd moet worden. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Stelt de prefixlijst in. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Stelt de versie van HTTP in. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Stelt de HTTP-proxy in. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Stelt een waarde in van de 'Referer'-header. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Stelt een waarde in die aangeeft of gegevens in segmenten moeten worden verzonden. |
| void [set_Timeout](./set_timeout/)(int) override | Stelt een tijdsduur in milliseconden in waarna het verzoek time-out krijgt. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Stelt een tijdsduur in milliseconden in waarna het verzoek time-out krijgt. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Stelt een waarde in die aangeeft of de eigenschap 'Credential' gelijk is aan de eigenschap 'DefaultCredentials'. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Stelt een waarde in van de 'User-Agent' header. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in op een zwakke pointer (in plaats van gedeelde). Stelt het wisselen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt het converteren van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [WebRequest](../webrequest/)
* Naamruimte [System::Net](../)
* Library [Aspose.Slides](../../)