---
title: CompareInfo
second_title: Aspose.Slides für C++ API-Referenz
description: "Führt kultursensible Zeichenkettenvergleiche durch. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 40
url: /de/system.globalization/compareinfo/
---
## CompareInfo Klasse

Führt kultursensible Zeichenkettenvergleiche durch. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class CompareInfo : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Vergleicht Zeichenketten. Nicht implementiert. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Vergleicht Zeichenketten. Nur die Modi Ordinal und OrdinalIgnoreCase werden unterstützt. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | Vergleicht einen Abschnitt einer Zeichenkette mit einem Abschnitt einer zweiten Zeichenkette. Nicht implementiert. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Vergleicht das Endsegment einer Zeichenkette mit dem Endsegment einer zweiten Zeichenkette mittels Zeichenkettenvergleichsmethoden. Nicht implementiert. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | Vergleicht das Endsegment einer Zeichenkette mit dem Endsegment einer zweiten Zeichenkette. Nicht implementiert. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Vergleicht einen Abschnitt einer Zeichenkette mit einem Abschnitt einer zweiten Zeichenkette mittels Zeichenkettenvergleichsmethoden. Nicht implementiert. |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | RTTI-Information. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| int [get_LCID](./get_lcid/)() const | Ermittelt die LCID der mit dem Vergleichsobjekt verknüpften Kultur. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Ermittelt den Namen der mit dem Vergleichsobjekt verknüpften Kultur. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | Ermittelt Informationen zur Sortier-Version. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Ermittelt [CompareInfo](./) für die angegebene Kultur und verwendet Zeichenkettenvergleichsmethoden in der angegebenen Assembly. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Ermittelt [CompareInfo](./) für die angegebene Kultur und verwendet Zeichenkettenvergleichsmethoden in der angegebenen Assembly. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | Ermittelt [CompareInfo](./) für die angegebene Kultur. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | Ermittelt [CompareInfo](./) für die angegebene Kultur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Ermittelt den Hashcode der Zeichenkette basierend auf den angegebenen Vergleichsoptionen. |
| int [GetHashCode](./gethashcode/)() const override | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Ermittelt das [SortKey](../sortkey/)-Objekt für die angegebene Zeichenkette unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | Ermittelt das [SortKey](../sortkey/)-Objekt für die angegebene Zeichenkette. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Sucht nach Teilzeichenkette. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Sucht nach Teilzeichenkette. Nur der Modus Ordinal wird unterstützt. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Sucht nach Teilzeichenkette. Nur der Modus Ordinal wird unterstützt. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Sucht nach dem angegebenen Zeichen. Nur der Modus Ordinal wird unterstützt. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Sucht nach Teilzeichenkette. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | Sucht nach dem angegebenen Zeichen. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Sucht nach Teilzeichenkette. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Sucht nach dem angegebenen Zeichen. Nur der Modus Ordinal wird unterstützt. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Sucht nach dem angegebenen Zeichen. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | Sucht nach dem angegebenen Zeichen. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Sucht nach Teilzeichenkette. Nur der Modus Ordinal wird unterstützt. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Sucht nach dem angegebenen Zeichen. Nur der Modus Ordinal wird unterstützt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Prüft, ob die angegebene Zeichenkette mit dem angegebenen Präfix beginnt, unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Prüft, ob die angegebene Zeichenkette mit dem angegebenen Präfix beginnt. |
| static **bool** [IsSortable](./issortable/)(char16_t) | Prüft, ob das angegebene Zeichen sortierbar ist. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | Prüft, ob die angegebene Zeichenkette sortierbar ist. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Prüft, ob die angegebene Zeichenkette mit dem angegebenen Suffix endet, unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Prüft, ob die angegebene Zeichenkette mit dem angegebenen Suffix endet. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Sucht das letzte Vorkommen der angegebenen Teilzeichenkette. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Sucht das letzte Vorkommen der angegebenen Teilzeichenkette unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Sucht das letzte Vorkommen des angegebenen Zeichens unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Sucht das letzte Vorkommen der angegebenen Zeichenkette. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Sucht das letzte Vorkommen der angegebenen Zeichenkette unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Sucht das letzte Vorkommen des angegebenen Zeichens unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Sucht das letzte Vorkommen der angegebenen Zeichenkette. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | Sucht das letzte Vorkommen des angegebenen Zeichens. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Sucht das letzte Vorkommen der angegebenen Zeichenkette unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Sucht das letzte Vorkommen des angegebenen Zeichens unter Verwendung der angegebenen Vergleichsoptionen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | Sucht das letzte Vorkommen des angegebenen Zeichens. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Sucht das letzte Vorkommen des angegebenen Zeichens. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Erlaubt das Umstellen von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die gemeinsame Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)