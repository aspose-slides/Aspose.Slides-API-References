---
title: TextWriter
second_title: "Aspose.Slides für C++ API-Referenz"
description: "Eine Basisklasse für Klassen, die Writer darstellen, die Zeichenfolgen an verschiedene Ziele schreiben. Objekte dieser Klasse sollten nur mit der System::MakeObject() Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 443
url: /de/system.io/textwriter/
---
## TextWriter Klasse

Eine Basisklasse für Klassen, die Writer darstellen, die Zeichenfolgen an verschiedene Ziele schreiben. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/) Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Pointer ein und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben.

```cpp
class TextWriter : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [Close](./close/)() | Schließt den Stream und gibt erworbene Ressourcen frei. |
| void [Dispose](./dispose/)() override | Gibt alle vom aktuellen Objekt verwendeten Ressourcen frei und schließt den zugrunde liegenden Stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztypenobjekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttypenobjekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual void [Flush](./flush/)() | Schreibt den Inhalt des Puffers in den zugrunde liegenden Stream. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Gibt die derzeit verwendete Kodierung zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Gibt das derzeit verwendete [IFormatProvider](../../system/iformatprovider/) Objekt zurück. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Gibt das derzeit verwendete [IFormatProvider](../../system/iformatprovider/) Objekt zurück. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Gibt eine Zeilenabschlusszeichenkette zurück. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Gibt eine Zeilenabschlusszeichenkette zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C# 'is' Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock() Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Sentry-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die geteilte Referenzzahl um den angegebenen Wert. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Setzt eine Zeilenabschlusszeichenkette. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die geteilte Referenzzahl. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die geteilte Referenzzahl zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/)) Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock() Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Sentry-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzahl. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzahl. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schreibt die String-Darstellung des angegebenen Objekts in den Stream. |
| virtual void [Write](./write/)(**bool**) | Schreibt die String-Darstellung des angegebenen booleschen Werts in den Stream. |
| virtual void [Write](./write/)(char_t) | Schreibt das angegebene Zeichen in den Stream. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Schreibt die String-Darstellung des angegebenen [Decimal](../../system/decimal/) Objekts in den Stream. |
| virtual void [Write](./write/)(**double**) | Schreibt die String-Darstellung des angegebenen double-Präzisions-Gleitkommawertes in den Stream. |
| virtual void [Write](./write/)(int) | Schreibt die String-Darstellung des angegebenen 32-Bit-Ganzzahlwertes in den Stream. |
| virtual void [Write](./write/)(**int64_t**) | Schreibt die String-Darstellung des angegebenen 64-Bit-Ganzzahlwertes in den Stream. |
| virtual void [Write](./write/)(**float**) | Schreibt die String-Darstellung des angegebenen single-Präzisions-Gleitkommawertes in den Stream. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Schreibt die angegebene Zeichenkette in den Stream. |
| virtual void [Write](./write/)(**uint32_t**) | Schreibt die String-Darstellung des angegebenen unsigned 32-Bit-Ganzzahlwertes in den Stream. |
| virtual void [Write](./write/)(**uint64_t**) | Schreibt die String-Darstellung des angegebenen unsigned 64-Bit-Ganzzahlwertes in den Stream. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Schreibt alle Zeichen aus dem angegebenen Array in den Stream. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Schreibt den angegebenen Teilbereich von UTF-16 Zeichen aus dem angegebenen Zeichenarray in den Stream. |
| virtual void [Write](./write/)(const char_t *) | Schreibt die angegebene C-Zeichenkette in den Stream. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Schreibt die String-Darstellung des angegebenen [TypeInfo](../../system/typeinfo/) Objekts in den Stream. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Schreibt die angegebenen Werte nach dem angegebenen Format in den Stream. |
| virtual void [WriteLine](./writeline/)() | Schreibt Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schreibt die String-Darstellung des angegebenen Objekts gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(**bool**) | Schreibt die String-Darstellung des angegebenen booleschen Werts gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(char_t) | Schreibt das angegebene Zeichen gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Schreibt die String-Darstellung des angegebenen [Decimal](../../system/decimal/) Objekts gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(**double**) | Schreibt die String-Darstellung des angegebenen double-Präzisions-Gleitkommawertes gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(int) | Schreibt die String-Darstellung des angegebenen 32-Bit-Ganzzahlwertes gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Schreibt die String-Darstellung des angegebenen 64-Bit-Ganzzahlwertes gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(**float**) | Schreibt die String-Darstellung des angegebenen single-Präzisions-Gleitkommawertes gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Schreibt die angegebene Zeichenkette gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Schreibt die String-Darstellung des angegebenen unsigned 32-Bit-Ganzzahlwertes gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Schreibt die String-Darstellung des angegebenen unsigned 64-Bit-Ganzzahlwertes gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Schreibt alle Zeichen aus dem angegebenen Array gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Schreibt den angegebenen Teilbereich von UTF-16 Zeichen aus dem angegebenen Zeichenarray gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Schreibt die angegebene C-Zeichenkette gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Schreibt die String-Darstellung des angegebenen [TypeInfo](../../system/typeinfo/) Objekts gefolgt von den Zeilenabschlusszeichen in den Stream. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Schreibt die angegebenen Werte nach dem angegebenen Format gefolgt von den Zeilenabschlusszeichen in den Stream. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| virtual  [~TextWriter](./~textwriter/)() | Destruktor. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf diese Klasse. |

## Siehe auch

* Klasse [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Bibliothek [Aspose.Slides](../../)