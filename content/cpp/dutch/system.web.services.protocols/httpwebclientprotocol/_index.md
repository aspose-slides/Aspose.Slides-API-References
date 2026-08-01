---
title: HttpWebClientProtocol
second_title: Aspose.Slides voor C++ API-referentie
description: "Deze basisklasse wordt gebruikt in alle XML Web service client-proxy's die HTTP gebruiken. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject()-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 14
url: /nl/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebProtocol klasse


Deze basisklasse wordt gebruikt in alle XML [Web](../../system.web/) service-client-proxy's die HTTP gebruiken. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Methods

| Methode | Beschrijving |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Annuleert de aanvraag. |
| virtual void [CheckForCookies](./checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Voegt cookies van het opgegeven verzoek toe aan de interne cookiecontainer. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-kommagelijkheid waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-kommagelijkheid waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Geeft een waarde die aangeeft of de client serveromleidingen volgt. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Retourneert de collectie van de clientcertificaten. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Retourneert de naam van de verbindingsgroep. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Haalt een container op die wordt gebruikt om cookies op te slaan. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Haalt de authenticatie-informatie op. |
| **bool** [get_EnableDecompression](./get_enabledecompression/)() | Geeft een waarde die aangeeft of decomprimeren is ingeschakeld. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Geeft een waarde die aangeeft of pre-authenticatie is ingeschakeld. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](./get_proxy/)() | Haalt proxy-informatie op. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | Haalt de codering op die wordt gebruikt voor client-verzoeken. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | Haalt de tijdspanne op die moet worden gewacht voordat het verzoek time-out. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Geeft een waarde die aangeeft of gedeelde verbindingen zijn ingeschakeld wanneer de client NTLM-authenticatie gebruikt. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | Haalt de XML [Web](../../system.web/) service-URI op. |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | Haalt de XML [Web](../../system.web/) service-URL op. |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | Geeft een waarde die aangeeft of de eigenschap 'Credential' gelijk is aan de eigenschap 'DefaultCredentials'. |
| [String](../../system/string/) [get_UserAgent](./get_useragent/)() | Haalt een waarde van de 'User-Agent'-header op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de gegevensstructuur van de referentieteller op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Stelt een waarde in die aangeeft of de client serveromleidingen volgt. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Stelt de naam van de verbindingsgroep in. |
| void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Stelt een container in die wordt gebruikt om cookies op te slaan. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Stelt de authenticatie-informatie in. |
| void [set_EnableDecompression](./set_enabledecompression/)(**bool**) | Stelt een waarde in die aangeeft of decomprimeren is ingeschakeld. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Stelt een waarde in die aangeeft of pre-authenticatie is ingeschakeld. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Stelt proxy-informatie in. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Stelt de codering in die wordt gebruikt voor client-verzoeken. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | Stelt de tijdspanne in die moet worden gewacht voordat het verzoek time-out. |
| void [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(**bool**) | Stelt een waarde in die aangeeft of gedeelde verbindingen zijn ingeschakeld wanneer de client NTLM-authenticatie gebruikt. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Stelt de XML [Web](../../system.web/) service-URI in. |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | Stelt de XML [Web](../../system.web/) service-URL in. |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | Stelt een waarde in die aangeeft of de eigenschap 'Credential' gelijk is aan de eigenschap 'DefaultCredentials'. |
| void [set_UserAgent](./set_useragent/)([String](../../system/string/)) | Stelt een waarde in voor de 'User-Agent'-header. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| void [UnregisterMapping](./unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne datastructuren. |

## Zie ook

* Klasse [WebClientProtocol](../webclientprotocol/)
* Naamruimte [System::Web::Services::Protocols](../)
* Bibliotheek [Aspose.Slides](../../)