---
title: IPAddress
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt die IP-Adresse dar. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 326
url: /de/system.net/ipaddress/
---
## IPAddress Klasse

Stellt die IP-Adresse dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class IPAddress : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergleicht Objekte unter Verwendung der C#-[Object.Equals](../../system/object/equals/)-Semantik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C#-[Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Gibt die Adressfamilie zurück. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Gibt einen Wert zurück, der angibt, ob die Adresse eine IPv4-Adresse ist und auf eine IPv6-Adresse abgebildet wird. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Gibt einen Wert zurück, der angibt, ob die Adresse eine IPv6-Link-Local-Adresse ist. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Gibt einen Wert zurück, der angibt, ob die Adresse eine globale IPv6-Multicast-Adresse ist. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Gibt einen Wert zurück, der angibt, ob die Adresse eine IPv6-Site-Local-Adresse ist. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Gibt einen Wert zurück, der angibt, ob die Adresse eine IPv6-Teredo-Adresse ist. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Ermittelt den Scope-Identifikator der IPv6-Adresse. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Gibt ein Byte-Array der IP-Adresse zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog zur C#-[Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Gibt einen Zeiger auf die Implementierung zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-[System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Konvertiert die angegebene Byte-Reihenfolge des Hosts in die entsprechende Netzwerk-Byte-Reihenfolge. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Konvertiert die angegebene Byte-Reihenfolge des Hosts in die entsprechende Netzwerk-Byte-Reihenfolge. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Konvertiert die angegebene Byte-Reihenfolge des Hosts in die entsprechende Netzwerk-Byte-Reihenfolge. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Konstruiert eine neue Instanz. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Konstruiert eine neue Instanz. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Konstruiert eine neue Instanz. |
|  [IPAddress](./ipaddress/)() | Konstruiert eine neue Instanz. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C#-„is“-Operator. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Gibt einen Wert zurück, der angibt, ob die angegebene Adresse eine Loopback-Adresse ist. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Mappt die Adresse auf die IPv4-Adresse. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Mappt die Adresse auf die IPv6-Adresse. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Konvertiert die angegebene Netzwerk-Byte-Reihenfolge in die entsprechende Host-Byte-Reihenfolge. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Konvertiert die angegebene Netzwerk-Byte-Reihenfolge in die entsprechende Host-Byte-Reihenfolge. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Konvertiert die angegebene Netzwerk-Byte-Reihenfolge in die entsprechende Host-Byte-Reihenfolge. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Konvertiert einen übergebenen String in eine Instanz der Klasse [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Setzt den Scope-Identifikator der IPv6-Adresse. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Setzt einen Zeiger auf die Implementierung. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Versucht, einen übergebenen String in eine Instanz der Klasse [IPAddress](./) zu konvertieren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Any](./any/) | Die IPv4-Adresse, die angibt, ob der Server auf allen Netzwerkschnittstellen lauschen muss. |
| static [Broadcast](./broadcast/) | Die IPv4-Broadcast-Adresse. |
| static [IPv6Any](./ipv6any/) | Die IPv6-Adresse, die angibt, ob der Server auf allen Netzwerkschnittstellen lauschen muss. |
| static [IPv6Loopback](./ipv6loopback/) | Die IPv6-Loopback-Adresse. |
| static [IPv6None](./ipv6none/) | Die IPv6-Adresse, die angibt, dass der Server keine Netzwerkschnittstelle lauschen darf. |
| static [Loopback](./loopback/) | Die IPv4-Loopback-Adresse. |
| static [None](./none/) | Die IPv4-Adresse, die angibt, dass der Server keine Netzwerkschnittstelle lauschen darf. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ImplPtr](./implptr/) | Ein Zeiger auf den Implementierungstyp. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Net](../)
* Bibliothek [Aspose.Slides](../../)