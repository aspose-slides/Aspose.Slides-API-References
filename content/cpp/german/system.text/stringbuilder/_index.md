---
title: StringBuilder
second_title: Aspose.Slides für C++ API Referenz
description: "Puffer zum schrittweisen Zusammenbauen von Zeichenketten. Dieser Typ kann entweder im Stack als Werttyp oder im Heap unter Verwendung der System::MakeObject()-Funktion alloziert werden. Sobald das Objekt alloziert ist, dürfen diese beiden Anwendungsfälle niemals vermischt werden: Das Verwenden von SmartPtr-Zeigern auf stack-alloziierte Objekte ist streng verboten."
type: docs
weight: 326
url: /de/system.text/stringbuilder/
---
## StringBuilder Klasse


[Buffer](../../system/buffer/) zum schrittweisen Zusammenbauen von Zeichenketten. Dieser Typ kann entweder im Stack als Werttyp oder im Heap unter Verwendung der [System::MakeObject()](../../system/makeobject/)-Funktion alloziert werden. Sobald das Objekt alloziert ist, dürfen diese beiden Anwendungsfälle niemals vermischt werden: Das Vorhandensein von [SmartPtr](../../system/smartptr/)-Zeigern auf stack-alloziierte Objekte ist streng verboten.

```cpp
class StringBuilder : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Fügt ein Zeichen zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Fügt Zeichen zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Fügt ein Zeichen-Array zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Fügt einen Teilbereich eines Zeichen-Arrays zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Fügt eine Zeichenkette zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Fügt einen Teilbereich einer Zeichenkette zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Fügt die Zeichenkettenrepräsentation eines Objekts zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Fügt den Inhalt eines Builders zu einem Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Fügt einen Gleitkommawert zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Fügt einen Gleitkommawert zum Builder hinzu. |
| [StringBuilder](./) * [Append](./append/)(int) | Fügt einen Ganzzahlwert zum Builder hinzu. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Fügt einen arithmetischen Wert zum Builder hinzu. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Fügt die Zeichenkettenrepräsentation eines Aufzählungswerts zum Builder hinzu. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Hängt eine formatierte Zeichenkette an den Builder an. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Hängt eine formatierte Zeichenkette an den Builder an. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Hängt ein Zeilenumbruchzeichen an den Builder an. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Hängt eine Zeichenkette, gefolgt von einem Zeilenumbruchzeichen, an den Builder an. |
| [StringBuilder](./) * [Clear](./clear/)() | Entfernt alle Zeichen aus dem Builder. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Kopiert die Builder-Daten in vorhandene Array-Positionen. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Stellt sicher, dass die Kapazität dieser Instanz von [System.Text.StringBuilder](./) mindestens den angegebenen Wert beträgt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C#-[Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| int [get_Capacity](./get_capacity/)() const | Gibt die aktuelle Kapazität des StringBuilders zurück. |
| int [get_Length](./get_length/)() const | Gibt die aktuelle Länge der im Builder befindlichen Zeichenkette zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-[Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C#-[System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| char_t [idx_get](./idx_get/)(int) const | Gibt das Zeichen an der angegebenen Position zurück. |
| void [idx_set](./idx_set/)(int, char_t) | Setzt das Zeichen an der angegebenen Position. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Fügt eine Zeichenkette an einer festen Position im Builder ein. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Fügt eine wiederholte Zeichenkette an einer festen Position im Builder ein. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Fügt ein Zeichen an einer festen Position im Builder ein. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Fügt Zeichen an einer festen Position im Builder ein. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Fügt einen Wert an einer festen Position im Builder ein. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| char_t [operator[]](./operator[]/)(int) const | Gibt das Zeichen an der angegebenen Position zurück. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Entfernt ein Fragment aus dem Builder. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ersetzt einen Teilstring im Builder. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Ersetzt einen Teilstring im angegebenen Bereich des Builders. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Ersetzt ein Zeichen im Builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Ersetzt ein Zeichen im angegebenen Bereich des Builders. |
| void [set_Capacity](./set_capacity/)(int) | Setzt die aktuelle Kapazität des StringBuilders. |
| void [set_Length](./set_length/)(int) | Schneidet den StringBuilder auf die angegebene Länge zu oder erweitert ihn. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [StringBuilder](./stringbuilder/)() | Konstruktor. |
| [StringBuilder](./stringbuilder/)(int) | Konstruktor. |
| [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Konstruktor. |
| [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Konstruktor. |
| [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Konstruktor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Gibt die aktuell im Builder enthaltene Zeichenkette zurück. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Gibt das aktuell im Builder enthaltene Teilstück zurück. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| [~StringBuilder](./~stringbuilder/)() | Destruktor. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Text](../)
* Bibliothek [Aspose.Slides](../../)