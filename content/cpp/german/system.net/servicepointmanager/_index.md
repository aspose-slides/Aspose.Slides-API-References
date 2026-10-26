---
title: ServicePointManager
second_title: Aspose.Slides für C++ API-Referenz
description: "Verwaltet die Lebenszyklusphasen (Erstellen, Pflegen und Löschen) der ServicePoint-Klasseninstanzen. Objekte dieser Klasse sollten nur mithilfe der System::MakeObject()-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 430
url: /de/system.net/servicepointmanager/
---
## ServicePointManager Klasse

Verwaltet die Lebenszyklusphasen (Erstellen, Pflegen und Löschen) der [ServicePoint](../servicepoint/) Klasseninstanzen. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ServicePointManager : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Ermittelt eine Zertifikatspolicy. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Ermittelt einen Wert, der angibt, ob das Zertifikat gegen die Sperrliste der Zertifizierungsstelle geprüft werden muss. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Ermittelt die maximale Anzahl gleichzeitiger Verbindungen, die von ServicePoint-class Instanzen erlaubt werden. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Ermittelt einen Timeout in Millisekunden, während dessen eine DNS-Auflösung als gültig gilt. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Ermittelt einen Wert, der angibt, ob eine DNS-Auflösung unter den zutreffenden IP-Adressen rotiert. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Gibt die Verschlüsselungsrichtlinie zurück, die von der aktuellen Instanz verwendet wird. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Ermittelt einen Wert, der angibt, ob ServicePoint-class Instanzen das 100-Continue-Verhalten verwenden. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Ermittelt die maximale Leerlaufzeit von ServicePoint-class Instanzen. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Ermittelt die maximale Anzahl von ServicePoint-class Instanzen, die von der aktuellen Instanz verwaltet werden können. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Ermittelt einen Wert, der angibt, ob die Ausgangsverbindungssockets die Option 'SO_REUSE_UNICASTPORT' verwenden. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Ermittelt den Sicherheitprotokolltyp, der von ServicePoint-class Instanzen verwendet wird, die von der aktuellen Instanz verwaltet werden. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Ermittelt den Rückruf, der zur Validierung eines Serverzertifikats verwendet wird. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Ermittelt einen Wert, der angibt, ob ServicePoint-class Instanzen den Nagle-Algorithmus verwenden. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is' Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, tatsächlich, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, tatsächlich, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Setzt eine Zertifikatspolicy. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Setzt einen Wert, der angibt, ob das Zertifikat gegen die Sperrliste der Zertifizierungsstelle geprüft werden muss. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Setzt die maximale Anzahl gleichzeitiger Verbindungen, die von ServicePoint-class Instanzen erlaubt werden. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Setzt einen Timeout in Millisekunden, während dessen eine DNS-Auflösung als gültig gilt. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Setzt einen Wert, der angibt, ob eine DNS-Auflösung unter den zutreffenden IP-Adressen rotiert. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Setzt einen Wert, der angibt, ob ServicePoint-class Instanzen das 100-Continue-Verhalten verwenden. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Setzt die maximale Leerlaufzeit von ServicePoint-class Instanzen. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Setzt die maximale Anzahl von ServicePoint-class Instanzen, die von der aktuellen Instanz verwaltet werden können. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Setzt einen Wert, der angibt, ob die Ausgangsverbindungssockets die Option 'SO_REUSE_UNICASTPORT' verwenden. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Setzt den Sicherheitprotokolltyp, der von ServicePoint-class Instanzen verwendet wird, die von der aktuellen Instanz verwaltet werden. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Setzt den Rückruf, der zur Validierung eines Serverzertifikats verwendet wird. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Setzt einen Wert, der angibt, ob ServicePoint-class Instanzen den Nagle-Algorithmus verwenden. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Setzt den Wert, der angibt, ob die 'Keep-Alive'-Option aktiviert ist. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/)) Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Die Standardanzahl nicht-persistenter Verbindungen. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Die Standardanzahl persistenter Verbindungen. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Net](../)
* Bibliothek [Aspose.Slides](../../)