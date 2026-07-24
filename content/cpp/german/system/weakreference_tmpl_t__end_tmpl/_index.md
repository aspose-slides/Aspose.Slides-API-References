---
title: WeakReference< T >
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine schwache Referenz dar, die ein Objekt referenziert, während das Objekt weiterhin gelöscht werden kann.
type: docs
weight: 1509
url: /de/system/weakreference_tmpl_t__end_tmpl/
---
## WeakReference< T > Klasse


Stellt eine schwache Referenz dar, die ein Objekt referenziert, während das Objekt weiterhin gelöscht werden kann.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ eines referenzierten Objekts. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Analog zum C# [System.Object.GetType()](../object/gettype/)-Aufruf. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Prüft, ob das referenzierte Objekt nicht null ist. |
| **bool** [operator!=](./operator_not_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Vergleicht das referenzierte Objekt mit einer anderen Instanz der WeakReference-Klasse. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Prüft, ob das referenzierte Objekt null ist. |
| **bool** [operator==](./operator_equal_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Vergleicht das referenzierte Objekt mit einer anderen Instanz der WeakReference-Klasse. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [reset](./reset/)() |  |
| void [SetTarget](./settarget/)(const [SmartPtr](../smartptr/)\<T\>\&) | Setzt das Objekt (das Ziel), auf das das aktuelle WeakReference-Objekt verweist. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog zur C# [Object.ToString()](../object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| **bool** [TryGetTarget](./trygettarget/)(const [SmartPtr](../smartptr/)\<T\>\&) const | Gibt das Objekt (das Ziel) zurück, auf das das aktuelle WeakReference-Objekt verweist. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementiert das C# typeof([System.Object](../object/))-Konstrukt. |
| void [Unlock](../object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
|  [WeakReference](./weakreference/)() | Standardkonstruktor. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor von nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&) | Initialisiert eine neue Instanz der WeakReference-Klasse, die das angegebene Objekt referenziert. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&, **bool**) | Initialisiert eine neue Instanz der WeakReference-Klasse, die das angegebene Objekt referenziert. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../object/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)