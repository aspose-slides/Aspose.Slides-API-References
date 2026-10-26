---
title: StringWriter
second_title: Aspose.Slides für C++ API-Referenz
description: "Implementiert einen TextWriter, der Informationen in einen String schreibt. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder über operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Umhüllen Sie diese Klasse stets in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 417
url: /de/system.io/stringwriter/
---
## StringWriter Klasse


Implementiert einen [TextWriter](../textwriter/), der Informationen in einen String schreibt. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Umhüllen Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Schließt den Stream und gibt erworbene Ressourcen frei. |
| void [Dispose](../textwriter/dispose/)() override | Gibt alle vom aktuellen Objekt genutzten Ressourcen frei und schließt den zugrunde liegenden Stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual void [Flush](../textwriter/flush/)() | Schreibt den Inhalt des Puffers in den zugrunde liegenden Stream. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Gibt die aktuell verwendete Kodierung zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Gibt das aktuell verwendete [IFormatProvider](../../system/iformatprovider/)-Objekt zurück. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Gibt das aktuell verwendete [IFormatProvider](../../system/iformatprovider/)-Objekt zurück. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Gibt einen Zeilenabschluss-String zurück. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Gibt einen Zeilenabschluss-String zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Gibt den aktuell verwendeten StringBuilder zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Setzt einen Zeilenabschluss-String. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Konstruiert eine neue Instanz von [StringWriter](./) mithilfe des angegebenen StringBuilder und [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Konstruiert eine neue Instanz von [StringWriter](./) mithilfe des angegebenen StringBuilder und [IFormatProvider](../../system/iformatprovider/) aus der aktuellen Kultur. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Konstruiert eine neue Instanz von [StringWriter](./) mithilfe des angegebenen [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)() | Konstruiert eine neue Instanz von [StringWriter](./) mithilfe von [IFormatProvider](../../system/iformatprovider/) aus der aktuellen Kultur. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Gibt den zugrunde liegenden String zurück. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [Write](./write/)(char_t) override | Schreibt das angegebene Zeichen in den Stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Schreibt den angegebenen Teilbereich von Zeichen aus dem angegebenen Zeichenarray in den Stream. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Schreibt den angegebenen String in den Stream. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts in den Stream. |
| virtual void [Write](../textwriter/write/)(**bool**) | Schreibt die Zeichenkettenrepräsentation des angegebenen booleschen Wertes in den Stream. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Schreibt die Zeichenkettenrepräsentation des angegebenen [Decimal](../../system/decimal/)-Objekts in den Stream. |
| virtual void [Write](../textwriter/write/)(**double**) | Schreibt die Zeichenkettenrepräsentation des angegebenen double-Präzisions-Floating-Point-Wertes in den Stream. |
| virtual void [Write](../textwriter/write/)(int) | Schreibt die Zeichenkettenrepräsentation des angegebenen 32-Bit-Ganzzahlwertes in den Stream. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Schreibt die Zeichenkettenrepräsentation des angegebenen 64-Bit-Ganzzahlwertes in den Stream. |
| virtual void [Write](../textwriter/write/)(**float**) | Schreibt die Zeichenkettenrepräsentation des angegebenen single-Precision-Floating-Point-Wertes in den Stream. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Schreibt die Zeichenkettenrepräsentation des angegebenen vorzeichenlosen 32-Bit-Ganzzahlwertes in den Stream. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Schreibt die Zeichenkettenrepräsentation des angegebenen vorzeichenlosen 64-Bit-Ganzzahlwertes in den Stream. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Schreibt alle Zeichen aus dem angegebenen Array in den Stream. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Schreibt den angegebenen C-String in den Stream. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Schreibt die Zeichenkettenrepräsentation des angegebenen [TypeInfo](../../system/typeinfo/)-Objekts in den Stream. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Schreibt die angegebenen Werte, formatiert gemäß dem angegebenen Format, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)() | Schreibt Zeilenabschlusszeichen in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schreibt die Zeichenkettenrepräsentation des angegebenen Objekts, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Schreibt die Zeichenkettenrepräsentation des angegebenen booleschen Wertes, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Schreibt das angegebene Zeichen, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Schreibt die Zeichenkettenrepräsentation des angegebenen [Decimal](../../system/decimal/)-Objekts, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Schreibt die Zeichenkettenrepräsentation des angegebenen double-Präzisions-Floating-Point-Wertes, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Schreibt die Zeichenkettenrepräsentation des angegebenen 32-Bit-Ganzzahlwertes, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Schreibt die Zeichenkettenrepräsentation des angegebenen 64-Bit-Ganzzahlwertes, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Schreibt die Zeichenkettenrepräsentation des angegebenen single-Precision-Floating-Point-Wertes, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Schreibt den angegebenen String, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Schreibt die Zeichenkettenrepräsentation des angegebenen vorzeichenlosen 32-Bit-Ganzzahlwertes, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Schreibt die Zeichenkettenrepräsentation des angegebenen vorzeichenlosen 64-Bit-Ganzzahlwertes, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Schreibt alle Zeichen aus dem angegebenen Array, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Schreibt den angegebenen Teilbereich von UTF-16-Zeichen aus dem angegebenen Zeichenarray, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Schreibt den angegebenen C-String, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Schreibt die Zeichenkettenrepräsentation des angegebenen [TypeInfo](../../system/typeinfo/)-Objekts, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Schreibt die angegebenen Werte, formatiert gemäß dem angegebenen Format, gefolgt von den Zeilenabschlusszeichen, in den Stream. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Siehe auch

* Klasse [TextWriter](../textwriter/)
* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)