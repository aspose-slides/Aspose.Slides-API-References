---
title: AuthenticatedStream
second_title: Aspose.Slides für C++ API-Referenz
description: "Enthält die Methoden zum Übergeben von Anmeldeinformationen über einen Stream. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Umwickeln Sie diese Klasse stets mit einem System::SmartPtr-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 1
url: /de/system.net.security/authenticatedstream/
---
## AuthenticatedStream Klasse

Contains the methods for passing credentials across a stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Methoden

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Startet eine asynchrone Leseoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Startet eine asynchrone Schreiboperation. |
| virtual void [Close](../../system.io/stream/close/)() | Schließt den Stream. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Kopiert Bytes in den angegebenen Stream. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Kopiert Bytes in den angegebenen Stream und verwendet die angegebene Puffergröße. |
| void [Dispose](../../system.io/stream/dispose/)() override | Gibt alle vom aktuellen Objekt genutzten Ressourcen frei und schließt den Stream. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wartet, bis die angegebene asynchrone Leseoperation abgeschlossen ist. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beendet eine asynchrone Schreiboperation. Wartet, bis die angegebene asynchrone Schreiboperation abgeschlossen ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual void [Flush](../../system.io/stream/flush/)() | Leert die Puffer dieses Streams und schreibt alle gepufferten Daten in den zugrunde liegenden Speicher. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Löscht asynchron alle Puffer dieses Streams, veranlasst, dass alle gepufferten Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Löscht asynchron alle Puffer dieses Streams, veranlasst, dass alle gepufferten Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen. |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | Bestimmt, ob der Stream lesbar ist. |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | Bestimmt, ob der Stream das Springen unterstützt. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Ermittelt einen Wert, der bestimmt, ob der aktuelle Stream zeitlich begrenzt werden kann. |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | Bestimmt, ob der Stream schreibbar ist. |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | Gibt einen Wert zurück, der anzeigt, ob die Authentifizierung erfolgreich übergeben wurde. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | Gibt einen Wert zurück, der anzeigt, ob die über diesen Stream gesendeten Daten verschlüsselt sind. |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Gibt einen Wert zurück, der anzeigt, ob ein Server und ein Client authentifiziert sind. |
| virtual **bool** [get_IsServer](./get_isserver/)() const | Gibt einen Wert zurück, der anzeigt, ob die lokale Seite der Verbindung der Server ist. |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | Gibt einen Wert zurück, der anzeigt, ob die über diesen Stream gesendeten Daten signiert sind. |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | Gibt den Stream zurück, der von den aktuellen Klasseninstanzen zum Senden und Empfangen von Daten verwendet wird. |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | Gibt die Länge des Streams in Bytes zurück. |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | Gibt die aktuelle Position des Streams zurück. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Ermittelt einen Wert in Millisekunden, der bestimmt, wie lange der Stream zu lesen versucht, bevor ein Timeout eintritt. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Ermittelt einen Wert in Millisekunden, der bestimmt, wie lange der Stream zu schreiben versucht, bevor ein Timeout eintritt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Liest asynchron eine Sequenz von Bytes aus dem aktuellen Stream, verschiebt die Position im Stream um die gelesene Byte-Anzahl und überwacht Abbruchanforderungen. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Liest asynchron eine Sequenz von Bytes aus dem aktuellen Stream, verschiebt die Position im Stream um die gelesene Byte-Anzahl und überwacht Abbruchanforderungen. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Liest ein einzelnes Byte aus dem Stream und gibt einen 32-Bit-Ganzzahlwert zurück, der dem gelesenen Byte entspricht. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | Setzt die Position des vom aktuellen Objekt repräsentierten Streams. |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | Setzt die Position des Streams. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Setzt einen Wert, der bestimmt, ob der aktuelle Stream zeitlich begrenzt werden kann. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Setzt einen Wert in Millisekunden, der bestimmt, wie lange der Stream zu lesen versucht, bevor ein Timeout eintritt. |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | Setzt die Länge des vom aktuellen Objekt repräsentierten Streams. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen weak Pointer (anstatt shared). Ermöglicht das Umschalten von Zeigern in Containern auf den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den weak Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den weak Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Span in den Stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Schreibt asynchron eine Sequenz von Bytes in den aktuellen Stream, verschiebt die aktuelle Position in diesem Stream um die geschriebene Byte-Anzahl und überwacht Abbruchanforderungen. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schreibt asynchron eine Sequenz von Bytes in den aktuellen Stream, verschiebt die aktuelle Position in diesem Stream um die geschriebene Byte-Anzahl und überwacht Abbruchanforderungen. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Schreibt den angegebenen unsigned 8-Bit-Integer-Wert in den Stream. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Ein Stream ohne zugrunde liegenden Speicher. |

## Siehe auch

* Klasse [Stream](../../system.io/stream/)
* Namensraum [System::Net::Security](../)
* Bibliothek [Aspose.Slides](../../)