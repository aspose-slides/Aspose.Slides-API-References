---
title: Group
second_title: Aspose.Slides für C++ API Referenz
description: "Ergebnis des Matchings, das von einer einzelnen Capturing-Gruppe durchgeführt wird. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 27
url: /de/system.text.regularexpressions/group/
---
## Gruppenklasse

Ergebnis des Matchings, das von einer einzelnen Capturing-Gruppe durchgeführt wird. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) allokiert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Kapseln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Group : public System::Text::RegularExpressions::Capture
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [AddCapture](./addcapture/)(const [CapturePtr](../captureptr/)\&) | Fügt eine Erfassung in die Gruppe ein. |
| [Capture](../capture/capture/)(const [UStringPtr](../ustringptr/)\&, int, int) | Konstruktor. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C#-[Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [CaptureCollectionPtr](../capturecollectionptr/) [get_Captures](./get_captures/)() | Gibt verfügbare Erfassungen zurück. |
| int [get_Index](../capture/get_index/)() const | Gibt den Index des erfassten Teilstrings zurück. |
| int [get_Length](../capture/get_length/)() const | Gibt die Länge des erfassten Teilstrings zurück. |
| **bool** [get_Success](./get_success/)() | Prüft, ob das Erfassen für diese Gruppe erfolgreich war. |
| [String](../../system/string/) [get_Value](../capture/get_value/)() const | Gibt den erfassten Teilstring zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-[Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C#-[System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| [Group](./group/)(const [UStringPtr](../ustringptr/)\&, int, int) | Konstruktor. |
| [Group](./group/)() | Konstruktor einer leeren Gruppe. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-`is`-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des geteilten Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| [String](../../system/string/) [ToString](../capture/tostring/)() const override | Gibt den erfassten Teilstring zurück. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert die C#-typeof([System.Object](../../system/object/))-Konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Capture](../capture/)
* Namensraum [System::Text::RegularExpressions](../)
* Bibliothek [Aspose.Slides](../../)