---
title: SoapHttpClientProtocol
second_title: Aspose.Slides för C++ API-referens
description: "Klientproxytjänsterna måste ärva denna klass när SOAP används. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 118
url: /sv/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol klass

Klientproxytjänsterna måste ärva denna klass när SOAP används. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Avbryter begäran. |
| virtual void [CheckForCookies](../httpwebclientprotocol/checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Lägger till kakor från den specificerade begäran till den interna cookiebehållaren. |
| void [Discover](./discover/)() | Binder den aktuella instansen till XML [Web](../../system.web/)-tjänsten. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **bool** [get_AllowAutoRedirect](../httpwebclientprotocol/get_allowautoredirect/)() | Hämtar ett värde som indikerar om klienten följer serveromdirigeringar. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](../httpwebclientprotocol/get_clientcertificates/)() | Returnerar samlingen av klientcertifikat. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Hämtar namnet på anslutningsgruppen. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](../httpwebclientprotocol/get_cookiecontainer/)() | Hämtar en behållare som används för att lagra kakor. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Hämtar autentiseringsinformationen. |
| **bool** [get_EnableDecompression](../httpwebclientprotocol/get_enabledecompression/)() | Hämtar ett värde som indikerar om dekomprimering är aktiverad. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Hämtar ett värde som indikerar om förautentisering är aktiverad. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](../httpwebclientprotocol/get_proxy/)() | Hämtar proxyinformation. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | Hämtar den kodning som används för att göra klientförfrågningar. |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() | Hämtar SOAP-versionen. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | Hämtar tidsintervallet att vänta innan begäran får timeout. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/get_unsafeauthenticatedconnectionsharing/)() | Hämtar ett värde som indikerar om anslutningsdelning är aktiverad när klienten använder NTLM-autentisering. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | Hämtar XML [Web](../../system.web/)-tjänstens URI. |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | Hämtar XML [Web](../../system.web/)-tjänstens URL. |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | Hämtar ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
| [String](../../system/string/) [get_UserAgent](../httpwebclientprotocol/get_useragent/)() | Hämtar ett värde för 'User-Agent'-huvudet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| void [InitializeSerializers](./initializeserializers/)(const [System::TypeInfo](../../system/typeinfo/)\&, [System::SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerImplementation](../../system.xml.serialization/xmlserializerimplementation/)\>, [String](../../system/string/)) | Initierar de interna fälten. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning av C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AllowAutoRedirect](../httpwebclientprotocol/set_allowautoredirect/)(**bool**) | Ställer in ett värde som indikerar om klienten följer serveromdirigeringar. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Ställer in namnet på anslutningsgruppen. |
| void [set_CookieContainer](../httpwebclientprotocol/set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Ställer in en behållare som används för att lagra kakor. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Ställer in autentiseringsinformationen. |
| void [set_EnableDecompression](../httpwebclientprotocol/set_enabledecompression/)(**bool**) | Ställer in ett värde som indikerar om dekomprimering är aktiverad. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Ställer in ett värde som indikerar om förautentisering är aktiverad. |
| void [set_Proxy](../httpwebclientprotocol/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Ställer in proxyinformation. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Ställer in den kodning som används för att göra klientförfrågningar. |
| void [set_SoapVersion](./set_soapversion/)([SoapProtocolVersion](../soapprotocolversion/)) | Ställer in SOAP-versionen. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | Ställer in tidsintervallet att vänta innan begäran får timeout. |
| void [set_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/set_unsafeauthenticatedconnectionsharing/)(**bool**) | Ställer in ett värde som indikerar om anslutningsdelning är aktiverad när klienten använder NTLM-autentisering. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Ställer in XML [Web](../../system.web/)-tjänstens URI. |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | Ställer in XML [Web](../../system.web/)-tjänstens URL. |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | Ställer in ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
| void [set_UserAgent](../httpwebclientprotocol/set_useragent/)([String](../../system/string/)) | Ställer in ett värde för 'User-Agent'-huvudet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument som en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
|  [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | Konstruerar en ny instans. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning-av C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| void [UnregisterMapping](../httpwebclientprotocol/unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [HttpWebClientProtocol](../httpwebclientprotocol/)
* Namnrymd [System::Web::Services::Protocols](../)
* Bibliotek [Aspose.Slides](../../)