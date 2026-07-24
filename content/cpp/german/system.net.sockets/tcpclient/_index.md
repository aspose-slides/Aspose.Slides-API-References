---
title: TcpClient
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Client für die TCP-Netzwerkdienste dar. Objekte dieser Klasse sollten ausschließlich mit der System::MakeObject()-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 66
url: /de/system.net.sockets/tcpclient/
---
## TcpClient Klasse

Stellt einen Client für die TCP-Netzwerkdienste dar. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class TcpClient : public System::IDisposable
```

## Methoden

| Method | Beschreibung |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Startet einen asynchronen Verbindungsaufbau. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Startet einen asynchronen Verbindungsaufbau. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Startet einen asynchronen Verbindungsaufbau. |
| void [Close](./close/)() | Schließt die Verbindung und gibt die aktuelle Instanz frei. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Stellt eine Verbindung zum angegebenen Remote-Host her. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Stellt eine Verbindung zum angegebenen Remote-Host her. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Stellt eine Verbindung zum angegebenen Remote-Host her. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Stellt eine Verbindung zum angegebenen Remote-Host her. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Tut nichts. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wartet, bis die angegebene asynchrone Verbindungsaufnahme abgeschlossen ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **int32_t** [get_Available](./get_available/)() | Gibt die Anzahl der empfangenen und zum Lesen bereitstehenden Bytes zurück. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Ruft den Socket ab. |
| **bool** [get_Connected](./get_connected/)() | Gibt einen Wert zurück, der angibt, ob der Socket mit dem Remote-Host verbunden ist. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Gibt einen Wert zurück, der anzeigt, ob die aktuelle Instanz nur einem Client die Nutzung eines Ports erlaubt. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Gibt einen Wert zurück, der angibt, ob der Socket das Schließen verzögert, um alle ausstehenden Daten zu senden. |
| **bool** [get_NoDelay](./get_nodelay/)() | Gibt einen Wert zurück, der anzeigt, ob die aktuelle Instanz den Nagle-Algorithmus verwendet. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Gibt die Größe des Puffers zurück, der zum Empfang von Daten verwendet wird. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Gibt einen Wert zurück, der die Zeitdauer angibt, nach der der Datenempfang abläuft. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Gibt die Größe des Puffers zurück, der zum Senden von Daten verwendet wird. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Gibt einen Wert zurück, der die Zeitdauer angibt, nach der das Senden von Daten abläuft. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | Gibt den Stream zurück, der zum Senden und Empfangen von Daten verwendet wird. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzanzahl um den angegebenen Wert. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Setzt den Socket. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Setzt einen Wert, der angibt, ob die aktuelle Instanz nur einem Client die Nutzung eines Ports erlaubt. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Setzt einen Wert, der angibt, ob der Socket das Schließen verzögern soll, um alle ausstehenden Daten zu senden. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Setzt einen Wert, der angibt, ob die aktuelle Instanz den Nagle-Algorithmus verwendet. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Setzt die Größe des Puffers, der zum Empfang von Daten verwendet wird. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Setzt einen Wert, der die Zeitdauer angibt, nach der der Datenempfang abläuft. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Setzt die Größe des Puffers, der zum Senden von Daten verwendet wird. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Setzt einen Wert, der die Zeitdauer angibt, nach der das Senden von Daten abläuft. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt zu einem geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzanzahl. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die gemeinsame Referenzanzahl und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Konstruiert eine neue Instanz. |
|  [TcpClient](./tcpclient/)() | Konstruiert eine neue Instanz. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | Konstruiert eine neue Instanz. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | Konstruiert eine neue Instanz. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzanzahl. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzanzahl. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| virtual  [~TcpClient](./~tcpclient/)() | Zerstört die aktuelle Instanz. |

## Siehe auch

* Klasse [IDisposable](../../system/idisposable/)
* Namensraum [System::Net::Sockets](../)
* Bibliothek [Aspose.Slides](../../)