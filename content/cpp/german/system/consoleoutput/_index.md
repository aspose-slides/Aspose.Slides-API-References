---
title: ConsoleOutput
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt den Standardausgabestream dar. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 209
url: /de/system/consoleoutput/
---
## ConsoleOutput Klasse

Stellt den Standardausgabestream dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Schließt den Stream und gibt erworbene Ressourcen frei. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Gibt alle vom aktuellen Objekt genutzten Ressourcen frei und schließt den zugrunde liegenden Stream. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergleicht Objekte mithilfe der C# [Object.Equals](../object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Schreibt den Inhalt des Puffers in den zugrunde liegenden Stream. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Gibt stets die ASCII-Kodierung zurück. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Gibt das aktuell verwendete [IFormatProvider](../iformatprovider/)-Objekt zurück. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Gibt das aktuell verwendete [IFormatProvider](../iformatprovider/)-Objekt zurück. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Gibt eine Zeilenende-Zeichenkette zurück. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Gibt eine Zeilenende-Zeichenkette zurück. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../object/lock/)() | Implementiert das Sperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-Konstruktor. Kopiert tatsächlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Setzt eine Zeilenende-Zeichenkette. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines Shared-Zeigers). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [Write](./write/)(**bool**) override | Gibt die Zeichenkettenrepräsentation des angegebenen bool-Werts an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen Objekts an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(char_t) override | Gibt den angegebenen Zeichenwert an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)([Decimal](../decimal/)) override | Gibt die Zeichenkettenrepräsentation des [Decimal](../decimal/)-Werts an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(**double**) override | Gibt die Zeichenkettenrepräsentation eines double-Präzisions-Gleitkommawertes an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(**int32_t**) override | Gibt die Zeichenkettenrepräsentation eines 32-Bit-Ganzzahlwertes an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(**int64_t**) override | Gibt die Zeichenkettenrepräsentation eines 64-Bit-Ganzzahlwertes an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(**float**) override | Gibt die Zeichenkettenrepräsentation eines single-Präzisions-Gleitkommawertes an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(const [String](../string/)\&) override | Gibt das angegebene Zeichenkettenobjekt an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(**uint32_t**) override | Gibt die Zeichenkettenrepräsentation eines vorzeichenlosen 32-Bit-Ganzzahlwertes an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(**uint64_t**) override | Gibt die Zeichenkettenrepräsentation eines vorzeichenlosen 64-Bit-Ganzzahlwertes an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen Zeichen-Arrays an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Gibt die Zeichenkettenrepräsentation eines Wertebereichs des angegebenen Zeichen-Arrays an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(const char_t *) override | Gibt die angegebene C-Zeichenkette an den von dem aktuellen Objekt dargestentlichen Ausgabestream aus. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen [TypeInfo](../typeinfo/)-Objekts an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Schreibt die Zeichenkettenrepräsentation des angegebenen 32-Bit-Ganzzahlwertes in den Stream. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Schreibt die angegebenen Werte, formatiert nach dem angegebenen Format, in den Stream. |
| void [WriteLine](./writeline/)() override | Gibt das aktuelle Zeilenende an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen Objekts, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(**bool**) override | Gibt die Zeichenkettenrepräsentation des angegebenen bool-Werts, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(char_t) override | Gibt den angegebenen Zeichenwert, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Gibt die Zeichenkettenrepräsentation des [Decimal](../decimal/)-Werts, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(**double**) override | Gibt die Zeichenkettenrepräsentation eines double-Präzisions-Gleitkommawertes, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(int) override | Gibt die Zeichenkettenrepräsentation eines 32-Bit-Ganzzahlwertes, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(**int64_t**) override | Gibt die Zeichenkettenrepräsentation eines 64-Bit-Ganzzahlwertes, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(**float**) override | Gibt die Zeichenkettenrepräsentation eines single-Präzisions-Gleitkommawertes, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Gibt das angegebene Zeichenkettenobjekt, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Gibt die Zeichenkettenrepräsentation eines vorzeichenlosen 32-Bit-Ganzzahlwertes, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Gibt die Zeichenkettenrepräsentation eines vorzeichenlosen 64-Bit-Ganzzahlwertes, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen Zeichen-Arrays, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Gibt die Zeichenkettenrepräsentation eines Wertebereichs des angegebenen Zeichen-Arrays, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(const char_t *) override | Gibt die angegebene C-Zeichenkette, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen [TypeInfo](../typeinfo/)-Objekts, gefolgt vom aktuellen Zeilenende, an den von dem aktuellen Objekt dargestellten Ausgabestream aus. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Schreibt die angegebenen Werte, formatiert nach dem angegebenen Format, gefolgt von den zeilenabschließenden Zeichen, in den Stream. |
| virtual  [~Object](../object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destruktor. |

## Siehe auch

* Klasse [TextWriter](../../system.io/textwriter/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)