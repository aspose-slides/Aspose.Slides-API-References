---
title: Semaphore
second_title: Aspose.Slides für C++ API-Referenz
description: "Semaphore-Implementierung. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 183
url: /de/system.threading/semaphore/
---
## Semaphore Klasse

[Semaphore](./) Implementierung. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Semaphore : public System::Threading::WaitHandle
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [Close](../waithandle/close/)() | Gibt jede mit dem Handle verbundene Ressource frei. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-Stil Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-Stil Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [wait_handle_t](../wait_handle_t/) [get_Handle](../waithandle/get_handle/)() | Erhält das Handle. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [Release](./release/)() | Gibt die Sperre des Semaphors frei. |
| int [Release](./release/)(int) | Gibt mehrere Sperren des Semaphors frei. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual **bool** [Reset](./reset/)() | Setzt das Semaphore in den nicht-signalisierten Zustand. Nicht unterstützt. |
|  [Semaphore](./semaphore/)(int, int) | Erstelle ein nicht benanntes Semaphore. |
|  [Semaphore](./semaphore/)(int, int, const [String](../../system/string/)\&) | Erstelle ein benanntes Semaphore. |
|  [Semaphore](./semaphore/)(int, int, const [String](../../system/string/)\&, **bool**\&) | Erstelle ein benanntes Semaphore. |
| virtual **bool** [Set](./set/)() | Setzt das Semaphore in den signalisierten Zustand. Nicht unterstützt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt einem geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | Wartet, bis alle Handles ausgelöst wurden. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | Wartet, bis alle Handles ausgelöst wurden. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | Wartet, bis alle Handles ausgelöst wurden. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | Wartet, bis einer der Handles ausgelöst wurde. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | Wartet, bis einer der Handles ausgelöst wurde. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | Wartet, bis einer der Handles ausgelöst wurde. |
| **bool** [WaitOne](./waitone/)() override | Sperrt das Semaphore. Führt bei Bedarf unbegrenztes Warten aus. |
| **bool** [WaitOne](./waitone/)(int) override | Sperrt das Semaphore. Führt bei Bedarf ein Warten aus. |
| virtual **bool** [WaitOne](../waithandle/waitone/)([TimeSpan](../../system/timespan/)) | Wartet, bis das Handle ausgelöst wird. |
| virtual **bool** [WaitOne](../waithandle/waitone/)(int, **bool**) | Wartet, bis das Handle ausgelöst wird. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| virtual  [~WaitHandle](../waithandle/~waithandle/)() | Destruktor. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Spezialwert, der von der Funktion zurückgegeben wird, wenn sonst der Index des signalisierten Objekts im Array zurückgegeben würde, falls das Timeout überschritten wird und nichts signalisiert. |

## Siehe Auch

* Klasse [WaitHandle](../waithandle/)
* Namensraum [System::Threading](../)
* Bibliothek [Aspose.Slides](../../)