---
title: Object
second_title: Aspose.Slides für C++ API-Referenz
description: Basisklasse, die die Verwendung der für die System.Object-Klasse in C# verfügbaren Methoden ermöglicht. Alle nicht trivialen Klassen, die in der übersetzten Umgebung verwendet werden, sollten von ihr erben.
type: docs
weight: 1132
url: /de/system/object/
---
## Objektklasse

Basisklasse, die die Verwendung der für die [System.Object](./)-Klasse in C# verfügbaren Methoden ermöglicht. Alle nicht triviale Klassen, die in der übersetzten Umgebung verwendet werden, sollten von ihr erben.

```cpp
class Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](./equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analog zur C# [Object.GetHashCode()](./gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](./gettype/)-Aufruf. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](./lock/)() | Implementiert die Sperrfunktion des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](./memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](./object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](./object/)([Object](./) const\&) | Copy-Konstruktor. Kopiert tatsächlich nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren beim Erzeugen von Unterklassen. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren beim Erzeugen von Unterklassen. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](./referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](./referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen weak-Pointer (statt shared). Ermöglicht das Umstellen von Zeigern in Containern auf weak-Modus. |
| int [SharedCount](./sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analog zur C# [Object.ToString()](./tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implementiert das C# typeof([System.Object](./))-Konstrukt. |
| void [Unlock](./unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Erhöht den weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](./weakrefremoved/)() | Verringert den weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](./~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [ptr](./ptr/) | Alias für den Smart-Pointer-Typ. |

## Bemerkungen

Zusammen mit den in der C# [System.Object](./)-Klasse verfügbaren Methoden ermöglicht es auch die Unterstützung einiger speziell für die übersetzte Code-Umgebung geltender Konzepte. Dazu gehören die Referenzzählung, die von Smart-Pointer-Klassen ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) verwendet wird, sowie weitere Dienste im Zusammenhang mit Speicherverwaltung, Debugging usw.

Jedes [Object](./) verfügt über zwei Referenzzähler: einen gemeinsamen Referenzzähler und einen weak-Referenzzähler. Der weak-Referenzzähler wird immer in einer separaten Datenstruktur gespeichert, nicht im [Object](./) selbst, wodurch weak-Pointer das referenzierte Objekt überleben können. Der gemeinsame Referenzzähler wird entweder im Objekt selbst oder in derselben separaten Struktur gespeichert, abhängig vom Zustand des Makros ENABLE_EXTERNAL_REFCOUNT. Standardmäßig ist er in Debug-Builds aktiviert und in Release-Builds deaktiviert. Wird der Smart-Pointer-Zähler im Objekt selbst gespeichert, wird die separate Datenstruktur nur erstellt, wenn weak-Pointer auf das Objekt existieren. Andernfalls wird sie zusammen mit dem Objekt selbst erstellt.

Alle Smart-Pointer verwenden diese beiden Referenzzähler und tragen zur selben, einzigen Besitzgruppe bei.

Wird eine [Object](./)-Unterklasse auf dem Stack erstellt, dürfen keine Smart-Pointer darauf erzeugt werden, sonst entsteht ein Problem beim Stack-Löschen.

Dieser Typ kann entweder auf dem Stack als Werttyp oder im Heap mittels der [System::MakeObject()](../makeobject/)-Funktion alloziiert werden. Sobald das Objekt alloziert ist, dürfen diese beiden Anwendungsfälle niemals vermischt werden: [SmartPtr](../smartptr/)-Pointer auf stack-allozierte Objekte sind strikt verboten.

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)