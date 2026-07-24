---
title: HttpWebRequest
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt die HTTP-Webanforderung dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 274
url: /de/system.net/httpwebrequest/
---
## HttpWebRequest Klasse


Represents the HTTP web request. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Methods

| Methode | Beschreibung |
| --- | --- |
| void [Abort](./abort/)() override | Bricht die aktuelle Anforderung ab. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Fügt den Header '[Range](../../system/range/)' zur aktuellen Anforderung hinzu. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Fügt den Header '[Range](../../system/range/)' zur aktuellen Anforderung hinzu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Startet eine asynchrone Operation, um einen Stream zum Schreiben von Daten in die Ressource zu erhalten. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Startet eine asynchrone Anforderung für die Ressource. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Erstellt eine neue Instanz der [WebRequest](../webrequest/) Klasse mit der angegebenen URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Erstellt eine neue Instanz der [WebRequest](../webrequest/) Klasse mit der angegebenen URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Erstellt einen [WebRequest](../webrequest/) Nachfolger für das angegebene URI-Schema. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Erstellt eine neue Instanz der [WebRequest](../webrequest/) Klasse mit der angegebenen URI. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Erstellt eine neue Instanz der [WebRequest](../webrequest/) Klasse mit der angegebenen URI. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Wartet, bis die angegebene asynchrone Operation zum Abrufen eines Streams abgeschlossen ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Wartet, bis die angegebene asynchrone Anforderung für die Ressource abgeschlossen ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Liefert den Wert des HTTP-Header 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Liefert einen Wert, der angibt, ob die Anforderung Weiterleitungen folgen soll. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Liefert einen Wert, der angibt, ob die von der Ressource empfangenen Daten gepuffert werden müssen. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Liefert einen Wert, der angibt, ob das Puffern für das Senden von Daten aktiviert ist. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Liefert die Cache-Richtlinie. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Liefert die Sammlung der Zertifikate, die mit der aktuellen Anforderung verbunden sind. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Liefert den Namen der Verbindungsgruppe. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Liefert die Anzahl der zu sendenden Bytes der Anforderungsdaten. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Liefert den MIME-Typ der Anforderung. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Liefert einen Timeout, um zu warten, bis der Statuscode 100-Continue empfangen wird. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Liefert einen Cookie-Container, der mit der aktuellen Web-Anforderung verknüpft ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Liefert die Authentifizierungsinformationen, die mit der aktuellen Anforderung verknüpft sind. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Liefert den globalen HTTP-Proxy. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Gibt einen Wert zurück, der angibt, ob eine Antwort empfangen wurde. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Liefert die Sammlung der HTTP-Header. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Liefert einen Wert, der angibt, ob die aktuelle Anforderung den Header 'Keep-Alive' enthalten muss. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Liefert die maximale Anzahl erlaubter Weiterleitungen. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Liefert die HTTP-Methode. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Liefert einen Wert, der angibt, ob die Anforderung vorab authentifiziert sein muss. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Liefert die Präfixliste. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Liefert den HTTP-Proxy. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Liefert den Wert des Headers 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Gibt die Anforderungs-URI zurück. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Liefert einen Wert, der angibt, ob Daten in Segmenten gesendet werden müssen. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Gibt einen Service-Punkt zurück, der die Netzwerkverbindung zur Ressource darstellt. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Gibt einen Wert zurück, der angibt, ob die aktuelle Anforderung einen Cookie-Container verwenden kann. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Liefert einen Zeitraum in Millisekunden, nach dem die Anforderung abläuft. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Liefert einen Wert, der angibt, ob die Eigenschaft 'Credential' gleich der Eigenschaft 'DefaultCredentials' ist. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Liefert den Wert des Headers 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Gibt den Stream zum Schreiben von Daten in die Ressource zurück. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Gibt die Web-Antwort zurück, die mit der aktuellen Web-Anforderung verknüpft ist. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Konstruiert eine neue Instanz. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Registriert den [WebRequest](../webrequest/) Nachfolger für die angegebene URI. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Setzt den Wert des HTTP-Header 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Setzt einen Wert, der angibt, ob die Anforderung Weiterleitungen folgen soll. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Setzt einen Wert, der angibt, ob die von der Ressource empfangenen Daten gepuffert werden müssen. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Setzt einen Wert, der angibt, ob das Puffern für das Senden von Daten aktiviert ist. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Setzt die Cache-Richtlinie. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Setzt die Sammlung der Zertifikate, die mit der aktuellen Anforderung verbunden sind. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Setzt den Namen der Verbindungsgruppe. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Setzt die Anzahl der zu sendenden Bytes der Anforderungsdaten. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Setzt den MIME-Typ der Anforderung. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Setzt einen Timeout, um zu warten, bis der Statuscode 100-Continue empfangen wird. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Setzt einen Cookie-Container, der mit der aktuellen Web-Anforderung verknüpft ist. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Setzt die Authentifizierungsinformationen, die mit der aktuellen Anforderung verknüpft sind. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Setzt den globalen HTTP-Proxy. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Setzt die Sammlung der HTTP-Header. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Setzt einen Wert, der angibt, ob die aktuelle Anforderung den Header 'Keep-Alive' enthalten muss. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Setzt die maximale Anzahl erlaubter Weiterleitungen. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Setzt die HTTP-Methode. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Setzt einen Wert, der angibt, ob die Anforderung vorab authentifiziert sein muss. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Setzt die Präfixliste. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Setzt die HTTP-Version. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Setzt den HTTP-Proxy. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Setzt den Wert des Headers 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Setzt einen Wert, der angibt, ob Daten in Segmenten gesendet werden müssen. |
| void [set_Timeout](./set_timeout/)(int) override | Setzt einen Zeitraum in Millisekunden, nach dem die Anforderung abläuft. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Setzt einen Zeitraum in Millisekunden, nach dem die Anforderung abläuft. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Setzt einen Wert, der angibt, ob die Eigenschaft 'Credential' gleich der Eigenschaft 'DefaultCredentials' ist. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Setzt den Wert des Headers 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen weak pointer (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe Auch

* Klasse [WebRequest](../webrequest/)
* Namensraum [System::Net](../)
* Bibliothek [Aspose.Slides](../../)