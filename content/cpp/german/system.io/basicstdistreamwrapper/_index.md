---
title: BasicSTDIStreamWrapper
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt einen System.IO.Stream-ähnlichen Wrapper für std::basic_istream und dessen abgeleitete Objekte dar. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 14
url: /de/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper Klasse

Stellt einen [System.IO.Stream](../stream/)-artigen Wrapper für std::basic_istream und seine abgeleiteten Objekte dar. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)-Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen wird. Umwickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Erzeugt eine neue Instanz von [BasicSTDIStreamWrapper](./). |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | Kopierkonstruktor. Gelöscht. |
|  virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Startet eine asynchrone Leseoperation. |
|  virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Startet eine asynchrone Schreiboperation. |
|  virtual void [Close](../stream/close/)() | Schließt den Stream. |
|  void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopiert Bytes in den angegebenen Stream. |
|  void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopiert Bytes in den angegebenen Stream unter Verwendung der angegebenen Puffergröße. |
|  void [Dispose](../stream/dispose/)() override | Gibt alle vom aktuellen Objekt genutzten Ressourcen frei und schließt den Stream. |
|  virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wartet, bis die angegebene asynchrone Leseoperation abgeschlossen ist. |
|  virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beendet eine asynchrone Schreiboperation. Wartet, bis die angegebene asynchrone Schreiboperation abgeschlossen ist. |
|  virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
|  static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
|  static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
|  static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
|  static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
|  virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
|  void [Flush](./flush/)() override | Leert die Puffer dieses Streams und schreibt alle gepufferten Daten in den zugrunde liegenden Speicher. Nicht unterstützt! |
|  virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leert asynchron alle Puffer dieses Streams, bewirkt, dass alle gepufferten Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen. |
|  [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Leert asynchron alle Puffer dieses Streams, bewirkt, dass alle gepufferten Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen. |
|  **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Bestimmt, ob der Stream das Suchen unterstützt. |
|  virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Gibt einen Wert zurück, der bestimmt, ob der aktuelle Stream zeitlich begrenzt werden kann. |
|  **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | Bestimmt, ob der Stream das Schreiben unterstützt. |
|  **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Gibt die Länge des Streams zurück. |
|  **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Gibt die aktuelle Position des Streams zurück. |
|  virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Gibt einen Wert in Millisekunden zurück, der bestimmt, wie lange der Stream versucht zu lesen, bevor ein Timeout eintritt. |
|  virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Gibt einen Wert in Millisekunden zurück, der bestimmt, wie lange der Stream versucht zu schreiben, bevor ein Timeout eintritt. |
|  Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
|  virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
|  virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
|  virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des vom targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
|  void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
|  virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
|  [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | Kopierzuweisungsoperator. Gelöscht. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopierzuweisungsoperator. Gelöscht. |
|  [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
|  **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Wenn der Wrapper-Modus binär ist, liest er die angegebene Anzahl von Bytes aus dem Stream, andernfalls liest er die angegebene Anzahl von Zeichen und konvertiert sie in den Typ **uint8_t**. Schreibt das Ergebnis des Lesens in das angegebene Byte-Array. |
|  **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
|  **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
|  virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in den angegebenen Byte-Span. |
|  virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Liest asynchron eine Byte-Sequenz aus dem aktuellen Stream, erhöht die Position im Stream um die gelesene Anzahl von Bytes und überwacht Abbruchanforderungen. |
|  [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Liest asynchron eine Byte-Sequenz aus dem aktuellen Stream, erhöht die Position im Stream um die gelesene Anzahl von Bytes und überwacht Abbruchanforderungen. |
|  int [ReadByte](./readbyte/)() override | Wenn der Wrapper-Modus binär ist, liest er ein einzelnes Byte aus dem letzten dekodierten Zeichenpuffer, andernfalls liest er ein einzelnes Zeichen aus dem Stream und konvertiert es in den Typ **uint8_t**. |
|  static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
|  static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
|  static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Verweist auf Vergleich eines Werttyp-Objekts mit nullptr. |
|  **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
|  **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
|  int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
|   [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI-Information. |
|  **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Setzt die Position des vom aktuellen Objekt repräsentierten Streams. |
|  void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Setzt die Position des Streams. |
|  virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Setzt einen Wert, der bestimmt, ob der aktuelle Stream zeitlich begrenzt werden kann. |
|  virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Setzt einen Wert in Millisekunden, der bestimmt, wie lange der Stream versucht zu lesen, bevor ein Timeout eintritt. |
|  void [SetLength](./setlength/)(**int64_t**) override | Setzt die Länge des vom aktuellen Objekt repräsentierten Streams. Nicht unterstützt! |
|  virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
|  int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
|  [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
|  int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopierkonstruktor. Gelöscht. |
|  virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte zu string. |
|  static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
|  void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
|  Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
|  void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
|  void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Wenn der Wrapper-Modus binär ist, schreibt er den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream, andernfalls konvertiert er den Teilbereich von Bytes aus dem angegebenen Byte-Array in den Typ char_type und schreibt das Ergebnis in den Stream. Nicht unterstützt! |
|  void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
|  void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
|  virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Span in den Stream. |
|  virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Schreibt asynchron eine Byte-Sequenz in den aktuellen Stream, erhöht die aktuelle Position im Stream um die geschriebene Anzahl von Bytes und überwacht Abbruchanforderungen. |
|  [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schreibt asynchron eine Byte-Sequenz in den aktuellen Stream, erhöht die aktuelle Position im Stream um die geschriebene Anzahl von Bytes und überwacht Abbruchanforderungen. |
|  void [WriteByte](./writebyte/)(**uint8_t**) override | Wenn der Wrapper-Modus binär ist, schreibt er den angegebenen unsigned 8-Bit-Integer-Wert in den Stream, andernfalls konvertiert er ihn in den Typ char_type und schreibt das Ergebnis in den Stream. Nicht unterstützt! |
|  virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Null](../stream/null/) | Ein Stream ohne zugrunde liegenden Speicher. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Siehe auch

* Klasse [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)