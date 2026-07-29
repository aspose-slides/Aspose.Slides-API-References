---
title: HttpWebClientProtocol
second_title: Aspose.Slides för C++ API-referens
description: "Denna basklass används i alla XML Web service-klientproxier som använder HTTP. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 14
url: /sv/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol klass


Denna basklass används i alla XML [Web](../../system.web/) tjänsteklientproxier som använder HTTP. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Avbryter begäran. |
| virtual void [CheckForCookies](./checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Lägger till kakor från den specificerade begäran till den interna kakbehållaren. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyper i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Hämtar ett värde som indikerar om klienten följer serveromdirigeringar. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Returnerar samlingen av klientcertifikaten. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Hämtar namnet på anslutningsgruppen. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Hämtar en behållare som används för att lagra kakor. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Hämtar autentiseringsinformationen. |
| **bool** [get_EnableDecompression](./get_enabledecompression/)() | Hämtar ett värde som indikerar om dekomprimering är aktiverad. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Hämtar ett värde som indikerar om förautentisering är aktiverad. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](./get_proxy/)() | Hämtar proxyinformation. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | Hämtar kodningen som används för att göra klientbegäran. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | Hämtar tidsintervallet att vänta innan begäran tidsöverskrider. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Hämtar ett värde som indikerar om anslutningsdelning är aktiverad när klienten använder NTLM-autentisering. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | Hämtar XML [Web](../../system.web/) tjänst-URI. |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | Hämtar XML [Web](../../system.web/) tjänst-URL. |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | Hämtar ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
| [String](../../system/string/) [get_UserAgent](./get_useragent/)() | Hämtar ett värde för 'User-Agent'-huvudet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-satts. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdeobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Ställer in ett värde som indikerar om klienten följer serveromdirigeringar. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Ställer in namnet på anslutningsgruppen. |
| void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Ställer in en behållare som används för att lagra kakor. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Ställer in autentiseringsinformationen. |
| void [set_EnableDecompression](./set_enabledecompression/)(**bool**) | Ställer in ett värde som indikerar om dekomprimering är aktiverad. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Ställer in ett värde som indikerar om förautentisering är aktiverad. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Ställer in proxyinformation. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Ställer in kodningen som används för att göra klientbegäran. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | Ställer in tidsintervallet att vänta innan begäran tidsöverskrider. |
| void [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(**bool**) | Ställer in ett värde som indikerar om anslutningsdelning är aktiverad när klienten använder NTLM-autentisering. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Ställer in XML [Web](../../system.web/) tjänst-URI. |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | Ställer in XML [Web](../../system.web/) tjänst-URL. |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | Ställer in ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
| void [set_UserAgent](./set_useragent/)([String](../../system/string/)) | Ställer in ett värde för 'User-Agent'-huvudet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument till en weak-pekare (istället för shared). Tillåter att byta pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning för C# lock()-satts upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakobjekt. |
| void [UnregisterMapping](./unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroyar objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [WebClientProtocol](../webclientprotocol/)
* Namnrymd [System::Web::Services::Protocols](../)
* Bibliotek [Aspose.Slides](../../)