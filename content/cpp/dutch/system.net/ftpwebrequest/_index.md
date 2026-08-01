---
title: FtpWebRequest
second_title: Aspose.Slides voor C++ API-referentie
description: Implementeert een File Transfer Protocol (FTP) client. Dummy klasse die het mogelijk maakt vertaalde code te koppelen met FtpWebRequest-referenties, maar deze niet uit te voeren. Bevat geen correct geïmplementeerde leden.
type: docs
weight: 170
url: /nl/system.net/ftpwebrequest/
---
## FtpWebRequest klasse

Implementeert een File Transfer Protocol (FTP) client. Dummy klasse die het mogelijk maakt gelinkte vertaalde code met [FtpWebRequest](./) verwijzingen, maar deze niet uit te voeren. Bevat geen correct geïmplementeerde leden.

```cpp
class FtpWebRequest : public System::Net::WebRequest
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual void [Abort](../webrequest/abort/)() | Annuleert het huidige verzoek. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](../webrequest/begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone bewerking om een stream te verkrijgen voor het schrijven van gegevens naar de bron. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](../webrequest/begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone aanvraag voor de bron. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Maakt een nieuwe instantie van de [WebRequest](../webrequest/) klasse aan met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een nieuwe instantie van de [WebRequest](../webrequest/) klasse aan met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een [WebRequest](../webrequest/) afstammeling voor het opgegeven URI-schema. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Maakt een nieuwe instantie van de [WebRequest](../webrequest/) klasse aan met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een nieuwe instantie van de [WebRequest](../webrequest/) klasse aan met de opgegeven URI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](../webrequest/endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone bewerking om een stream te verkrijgen voltooid is. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](../webrequest/endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone aanvraag voor de bron voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Haalt het cachebeleid op. |
| virtual [System::String](../../system/string/) [get_ConnectionGroupName](../webrequest/get_connectiongroupname/)() | Haalt de naam van de verbindingsgroep op. |
| virtual **int64_t** [get_ContentLength](../webrequest/get_contentlength/)() | Haalt het aantal bytes van de verzoekgegevens op die verzonden moeten worden. |
| virtual [String](../../system/string/) [get_ContentType](../webrequest/get_contenttype/)() | Haalt het MIME-type van het verzoek op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](../webrequest/get_credentials/)() | Haalt authenticatie-informatie op die aan het huidige verzoek is gekoppeld. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Haalt de globale HTTP-proxy op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](../webrequest/get_headers/)() | Haalt de collectie van de HTTP-headers op. |
| virtual [String](../../system/string/) [get_Method](../webrequest/get_method/)() | Haalt de HTTP-methode op. |
| virtual **bool** [get_PreAuthenticate](../webrequest/get_preauthenticate/)() | Haalt een waarde op die aangeeft of het verzoek vooraf moet worden geauthenticeerd. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Haalt de prefixlijst op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](../webrequest/get_proxy/)() | Haalt de HTTP-proxy op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](../webrequest/get_requesturi/)() | Retourneert de aanvraag-URI. |
| virtual **int32_t** [get_Timeout](../webrequest/get_timeout/)() | Haalt een tijdsduur in milliseconden op waarna het verzoek een time-out krijgt. |
| virtual **bool** [get_UseDefaultCredentials](../webrequest/get_usedefaultcredentials/)() | Haalt een waarde op die aangeeft of de eigenschap 'Credential' gelijk is aan de eigenschap 'DefaultCredentials'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van de C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt het mogelijk aangepaste objecten te hashen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](../webrequest/getrequeststream/)() | Retourneert de stream voor het schrijven van gegevens naar de bron. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](../webrequest/getresponse/)() | Retourneert de webrespons die aan het huidige webverzoek is gekoppeld. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van de C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analog van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waarschuwingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt het klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Registreert de [WebRequest](../webrequest/) afstammeling voor de opgegeven URI. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Stelt het cachebeleid in. |
| virtual void [set_ConnectionGroupName](../webrequest/set_connectiongroupname/)([System::String](../../system/string/)) | Stelt de naam van de verbindingsgroep in. |
| virtual void [set_ContentLength](../webrequest/set_contentlength/)(**int64_t**) | Stelt het aantal bytes van de verzoekgegevens in die verzonden moeten worden. |
| virtual void [set_ContentType](../webrequest/set_contenttype/)([String](../../system/string/)) | Stelt het MIME-type van het verzoek in. |
| virtual void [set_Credentials](../webrequest/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Stelt authenticatie-informatie in die aan het huidige verzoek is gekoppeld. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Stelt de globale HTTP-proxy in. |
| virtual void [set_Headers](../webrequest/set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) | Stelt de collectie van de HTTP-headers in. |
| virtual void [set_Method](../webrequest/set_method/)([String](../../system/string/)) | Stelt de HTTP-methode in. |
| virtual void [set_PreAuthenticate](../webrequest/set_preauthenticate/)(**bool**) | Stelt een waarde in die aangeeft of het verzoek vooraf moet worden geauthenticeerd. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Stelt de prefixlijst in. |
| virtual void [set_Proxy](../webrequest/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Stelt de HTTP-proxy in. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Stelt een tijdsduur in milliseconden in waarna het verzoek een time-out krijgt. |
| virtual void [set_UseDefaultCredentials](../webrequest/set_usedefaultcredentials/)(**bool**) | Stelt een waarde in die aangeeft of de eigenschap 'Credential' gelijk is aan de eigenschap 'DefaultCredentials'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat het wisselen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van de C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het mogelijk aangepaste objecten naar een string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waarschuwingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Bibliotheek [Aspose.Slides](../../)