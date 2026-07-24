---
title: SoapHttpClientProtocol
second_title: Aspose.Slides für C++ API Referenz
description: "Die Client-Proxy-Dienste müssen diese Klasse erben, wenn SOAP verwendet wird. Objekte dieser Klasse sollten nur mithilfe der Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 118
url: /de/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol Klasse


Die Client-Proxy-Dienste müssen diese Klasse erben, wenn SOAP verwendet wird. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../../system/makeobject/)-Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Bricht die Anforderung ab. |
| virtual void [CheckForCookies](../httpwebclientprotocol/checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Fügt Cookies aus der angegebenen Anforderung zum internen Cookie-Container hinzu. |
| void [Discover](./discover/)() | Bindet die aktuelle Instanz an den XML [Web](../../system.web/)-Dienst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_AllowAutoRedirect](../httpwebclientprotocol/get_allowautoredirect/)() | Gibt einen Wert zurück, der angibt, ob der Client Server-Weiterleitungen folgt. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](../httpwebclientprotocol/get_clientcertificates/)() | Gibt die Sammlung der Client-Zertifikate zurück. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Gibt den Namen der Verbindungsgruppe zurück. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](../httpwebclientprotocol/get_cookiecontainer/)() | Gibt einen Container zurück, der zum Speichern von Cookies verwendet wird. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Gibt die Authentifizierungsinformationen zurück. |
| **bool** [get_EnableDecompression](../httpwebclientprotocol/get_enabledecompression/)() | Gibt einen Wert zurück, der angibt, ob Dekompression aktiviert ist. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Gibt einen Wert zurück, der angibt, ob Vor-Authentifizierung aktiviert ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](../httpwebclientprotocol/get_proxy/)() | Gibt Proxy-Informationen zurück. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | Gibt die Kodierung zurück, die für die Client-Anfragen verwendet wird. |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() | Gibt die SOAP-Version zurück. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | Gibt den Zeitraum zurück, der vor einem Timeout der Anfrage wartet. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/get_unsafeauthenticatedconnectionsharing/)() | Gibt einen Wert zurück, der angibt, ob die Verbindungsfreigabe aktiviert ist, wenn der Client NTLM-Authentifizierung verwendet. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | Gibt die XML [Web](../../system.web/)-Dienst-URI zurück. |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | Gibt die XML [Web](../../system.web/)-Dienst-URL zurück. |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | Gibt einen Wert zurück, der angibt, ob die Eigenschaft 'Credential' gleich der Eigenschaft 'DefaultCredentials' ist. |
| [String](../../system/string/) [get_UserAgent](../httpwebclientprotocol/get_useragent/)() | Gibt einen Wert des 'User-Agent'-Headers zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| void [InitializeSerializers](./initializeserializers/)(const [System::TypeInfo](../../system/typeinfo/)\&, [System::SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerImplementation](../../system.xml.serialization/xmlserializerimplementation/)\>, [String](../../system/string/)) | Initialisiert die internen Felder. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz einen Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_AllowAutoRedirect](../httpwebclientprotocol/set_allowautoredirect/)(**bool**) | Setzt einen Wert, der angibt, ob der Client Server-Weiterleitungen folgt. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Setzt den Namen der Verbindungsgruppe. |
| void [set_CookieContainer](../httpwebclientprotocol/set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Setzt einen Container, der zum Speichern von Cookies verwendet wird. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Setzt die Authentifizierungsinformationen. |
| void [set_EnableDecompression](../httpwebclientprotocol/set_enabledecompression/)(**bool**) | Setzt einen Wert, der angibt, ob Dekompression aktiviert ist. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Setzt einen Wert, der angibt, ob Vor-Authentifizierung aktiviert ist. |
| void [set_Proxy](../httpwebclientprotocol/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Setzt Proxy-Informationen. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Setzt die Kodierung, die für die Client-Anfragen verwendet wird. |
| void [set_SoapVersion](./set_soapversion/)([SoapProtocolVersion](../soapprotocolversion/)) | Setzt die SOAP-Version. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | Setzt den Zeitraum, der vor einem Timeout der Anfrage wartet. |
| void [set_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/set_unsafeauthenticatedconnectionsharing/)(**bool**) | Setzt einen Wert, der angibt, ob die Verbindungsfreigabe aktiviert ist, wenn der Client NTLM-Authentifizierung verwendet. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Setzt die XML [Web](../../system.web/)-Dienst-URI. |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | Setzt die XML [Web](../../system.web/)-Dienst-URL. |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | Setzt einen Wert, der angibt, ob die Eigenschaft 'Credential' gleich der Eigenschaft 'DefaultCredentials' ist. |
| void [set_UserAgent](../httpwebclientprotocol/set_useragent/)([String](../../system/string/)) | Setzt einen Wert des 'User-Agent'-Headers. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | Konstruiert eine neue Instanz. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| void [UnregisterMapping](../httpwebclientprotocol/unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [HttpWebClientProtocol](../httpwebclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.Slides](../../)