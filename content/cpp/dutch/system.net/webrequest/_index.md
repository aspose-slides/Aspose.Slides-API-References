---
title: WebRequest
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een webverzoek voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of beweringsfouten oplevert. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 508
url: /nl/system.net/webrequest/
---
## WebRequest klasse

Representeert een webverzoek. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of beweringsfouten oplevert. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class WebRequest : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual void [Abort](./abort/)() | Annuleert het huidige verzoek. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Start een asynchrone bewerking om een stream te verkrijgen voor het schrijven van gegevens naar de bron. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Start een asynchrone aanvraag voor de bron. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [Create](./create/)([String](../../system/string/)) | Maakt een nieuwe instantie van de [WebRequest](./) klasse met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [Create](./create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een nieuwe instantie van de [WebRequest](./) klasse met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [CreateDefault](./createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een [WebRequest](./) afstammeling voor het opgegeven URI-schema. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](./createhttp/)([String](../../system/string/)) | Maakt een nieuwe instantie van de [WebRequest](./) klasse met de opgegeven URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](./createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Maakt een nieuwe instantie van de [WebRequest](./) klasse met de opgegeven URI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone bewerking om een stream te verkrijgen voltooid is. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone aanvraag voor de bron voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](./get_cachepolicy/)() | Haalt het cachebeleid op. |
| virtual [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() | Haalt de naam van de verbindingsgroep op. |
| virtual **int64_t** [get_ContentLength](./get_contentlength/)() | Haalt het aantal bytes aan verzoekgegevens op die verzonden moeten worden. |
| virtual [String](../../system/string/) [get_ContentType](./get_contenttype/)() | Haalt het MIME-type van het verzoek op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() | Haalt authenticatie-informatie op die aan het huidige verzoek is gekoppeld. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](./get_defaultwebproxy/)() | Haalt de globale HTTP-proxy op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() | Haalt de verzameling van de HTTP-headers op. |
| virtual [String](../../system/string/) [get_Method](./get_method/)() | Haalt de HTTP-methode op. |
| virtual **bool** [get_PreAuthenticate](./get_preauthenticate/)() | Haalt een waarde op die aangeeft of het verzoek vooraf moet worden geauthenticeerd. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](./get_prefixlist/)() | Haalt de prefixlijst op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() | Haalt de HTTP-proxy op. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() | Retourneert de verzoek-URI. |
| virtual **int32_t** [get_Timeout](./get_timeout/)() | Haalt een tijdsduur in milliseconden op waarna het verzoek zal verlopen. |
| virtual **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Haalt een waarde op die aangeeft of de eigenschap 'Credential' gelijk is aan de eigenschap 'DefaultCredentials'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() | Retourneert de stream voor het schrijven van gegevens naar de bron. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() | Retourneert de webrespons die aan het huidige webverzoek is gekoppeld. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie vertegenwoordigt van het type dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-construeren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-construeren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| static **bool** [RegisterPrefix](./registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Registreert de [WebRequest](./) afstammeling voor de opgegeven URI. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_CachePolicy](./set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Stelt het cachebeleid in. |
| virtual void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) | Stelt de naam van de verbindingsgroep in. |
| virtual void [set_ContentLength](./set_contentlength/)(**int64_t**) | Stelt het aantal bytes aan verzoekgegevens in die verzonden moeten worden. |
| virtual void [set_ContentType](./set_contenttype/)([String](../../system/string/)) | Stelt het MIME-type van het verzoek in. |
| virtual void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Stelt de authenticatie-informatie in die aan het huidige verzoek is gekoppeld. |
| static void [set_DefaultWebProxy](./set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Stelt de globale HTTP-proxy in. |
| virtual void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) | Stelt de verzameling van de HTTP-headers in. |
| virtual void [set_Method](./set_method/)([String](../../system/string/)) | Stelt de HTTP-methode in. |
| virtual void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) | Stelt een waarde in die aangeeft of het verzoek vooraf moet worden geauthenticeerd. |
| static void [set_PrefixList](./set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Stelt de prefixlijst in. |
| virtual void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Stelt de HTTP-proxy in. |
| virtual void [set_Timeout](./set_timeout/)(**int32_t**) | Stelt een tijdsduur in milliseconden in waarna het verzoek zal verlopen. |
| virtual void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | Stelt een waarde in die aangeeft of de eigenschap 'Credential' gelijk is aan de eigenschap 'DefaultCredentials'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Net](../)
* Bibliotheek [Aspose.Slides](../../)