---
title: ServicePoint
second_title: Aspose.Slides für C++ API-Referenz
description: "Bietet die Verwaltung von HTTP-Verbindungen. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 417
url: /de/system.net/servicepoint/
---
## ServicePoint Klasse


Bietet die Verwaltung von HTTP-Verbindungen. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals Instanzen dieses Typs im Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ServicePoint : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | Schließt und entfernt Verbindungen, die zur angegebenen Verbindungsgruppe gehören. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyps-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyps-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, auch nicht zu NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, auch nicht zu NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Gibt die Server-URI zurück, zu der die aktuelle Instanz verbindet. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | Liefert das Delegat, das verwendet wird, um lokale [IPEndPoint](../ipendpoint/) mit der aktuellen Instanz zu verknüpfen. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | Gibt ein Zertifikat zurück, das von der aktuellen Instanz verwendet wird. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | Gibt das zuletzt verwendete Client-Zertifikat zurück. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Liefert einen Timeout in Millisekunden, nach dem aktive [ServicePoint](./) geschlossen werden. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | Liefert die maximale Anzahl von Verbindungen, die von der aktuellen Instanz erlaubt sind. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | Gibt den Verbindungsnamen zurück. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | Gibt die Anzahl geöffneter Verbindungen zurück. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | Liefert einen Wert, der angibt, ob das 100-Continue-Verhalten verwendet wird. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | Gibt Datum und Uhrzeit der letzten Verbindung zu einem Host zurück. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | Liefert eine Zeitspanne in Millisekunden, nach der eine Leerlaufverbindung geschlossen wird. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | Gibt die HTTP-Version zurück. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Liefert die Größe des Empfangspuffers. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | Gibt einen Wert zurück, der anzeigt, ob die aktuelle Instanz Pipeline-Verbindungen unterstützt. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Liefert einen Wert, der angibt, ob der Nagle-Algorithmus von den von der aktuellen Instanz verwalteten Verbindungen verwendet wird. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkter Aufruf oder Verwendung des [LockContext](../../system/lockcontext/)-Wächterobjekts. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyps-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialfall von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialfall von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | Setzt das Delegat, das verwendet wird, um lokale [IPEndPoint](../ipendpoint/) mit der aktuellen Instanz zu verknüpfen. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | Setzt einen Timeout in Millisekunden, nach dem aktive [ServicePoint](./) geschlossen werden. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | Setzt die maximale Anzahl von Verbindungen, die von der aktuellen Instanz erlaubt sind. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Setzt einen Wert, der angibt, ob das 100-Continue-Verhalten verwendet wird. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | Setzt eine Zeitspanne in Millisekunden, nach der eine Leerlaufverbindung geschlossen wird. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Setzt die Größe des Empfangspuffers. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Setzt einen Wert, der angibt, ob der Nagle-Algorithmus von den von der aktuellen Instanz verwalteten Verbindungen verwendet wird. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Setzt den Wert, der angibt, ob die 'Keep-Alive'-Option aktiviert ist. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkter Aufruf oder Verwendung des [LockContext](../../system/lockcontext/)-Wächterobjekts. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Net](../)
* Bibliothek [Aspose.Slides](../../)