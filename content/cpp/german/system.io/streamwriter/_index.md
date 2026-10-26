---
title: StreamWriter
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Writer dar, der Zeichen in einen Bytestrom schreibt. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse immer in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 391
url: /de/system.io/streamwriter/
---
## StreamWriter Klasse

Stellt einen Writer dar, der Zeichen in einen Bytestrom schreibt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Close](./close/)() override | Schließt den Stream und gibt erworbene Ressourcen frei. |
| void [Dispose](./dispose/)() override | Gibt alle vom aktuellen Objekt verwendeten Ressourcen frei und schließt den zugrunde liegenden Stream. |
| virtual void [Dispose](./dispose/)(**bool**) | Gibt alle vom aktuellen Objekt verwendeten Ressourcen frei und schließt den zugrunde liegenden Stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den Semantiken von C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| void [Flush](./flush/)() override | Leert den Inhalt des Puffers in den zugrunde liegenden Stream und leert anschließend den zugrunde liegenden Stream. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Gibt einen Wert zurück, der angibt, ob [StreamWriter](./) die Daten jedes Mal, wenn die Methode [StreamWriter::Write](./write/) aufgerufen wird, in den zugrunde liegenden Stream leert. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Gibt einen Shared-Pointer auf ein Objekt zurück, das den zugrunde liegenden Stream repräsentiert. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Gibt die aktuell verwendete Kodierung zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Gibt das aktuell verwendete [IFormatProvider](../../system/iformatprovider/)-Objekt zurück. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Gibt das aktuell verwendete [IFormatProvider](../../system/iformatprovider/)-Objekt zurück. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Gibt einen Zeilenabschluss-String zurück. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Gibt einen Zeilenabschluss-String zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentinel-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Gibt einen Wert zurück, der angibt, ob [StreamWriter](./) die Daten jedes Mal, wenn die Methode [StreamWriter::Write](./write/) aufgerufen wird, in den zugrunde liegenden Stream leert. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Setzt einen Zeilenabschluss-String. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Konstruiert eine Instanz des [StreamWriter](./)-Objekts, das Zeichen in den angegebenen zugrunde liegenden Stream schreibt, UTF-8-Kodierung verwendet und einen Puffer mit Standardgröße von 1024 Byte nutzt. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Konstruiert eine Instanz des [StreamWriter](./)-Objekts, das Zeichen in den angegebenen zugrunde liegenden Stream schreibt, die angegebene Kodierung verwendet und einen Puffer mit Standardgröße von 1024 Byte nutzt. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Konstruiert eine Instanz des [StreamWriter](./)-Objekts, das Zeichen in den angegebenen zugrunde liegenden Stream schreibt, die angegebene Kodierung verwendet und einen Puffer der angegebenen Größe nutzt. Ein Parameter gibt an, ob der zugrunde liegende Stream geschlossen werden soll, wenn das [StreamWriter](./)-Objekt freigegeben wird. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Konstruiert eine Instanz des [StreamWriter](./)-Objekts, das Zeichen in die angegebene Datei schreibt, UTF-8-Kodierung verwendet und einen Puffer mit Standardgröße von 1024 Byte nutzt. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Konstruiert eine Instanz des [StreamWriter](./)-Objekts, das Zeichen in die angegebene Datei schreibt, die angegebene Kodierung verwendet und einen Puffer mit Standardgröße von 1024 Byte nutzt. Ein Parameter gibt an, ob die Daten an die Datei angehängt oder die Datei überschrieben werden soll. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Konstruiert eine Instanz des [StreamWriter](./)-Objekts, das Zeichen in die angegebene Datei schreibt, die angegebene Kodierung und Puffergröße verwendet. Ein Parameter gibt an, ob die Daten an die Datei angehängt oder die Datei überschrieben werden soll. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentinel-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [Write](./write/)(char_t) override | Schreibt das angegebene Zeichen in den Stream. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Schreibt die angegebene Zeichenkette in den Stream. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Schreibt die String-Repräsentation des angegebenen Objekts in den Stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Schreibt alle Zeichen des angegebenen Arrays in den Stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Schreibt den angegebenen Teilbereich von UTF-16-Zeichen des angegebenen Zeichenarrays in den Stream. |
| void [Write](./write/)(const char_t *) override | Schreibt die angegebene C-String in den Stream. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Schreibt die String-Repräsentation des angegebenen Objekts in den Stream. |
| virtual void [Write](../textwriter/write/)(**bool**) | Schreibt die String-Repräsentation des angegebenen booleschen Werts in den Stream. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Schreibt die String-Repräsentation des angegebenen [Decimal](../../system/decimal/)-Objekts in den Stream. |
| virtual void [Write](../textwriter/write/)(**double**) | Schreibt die String-Repräsentation des angegebenen double-Präzisions-Gleitkommawerts in den Stream. |
| virtual void [Write](../textwriter/write/)(int) | Schreibt die String-Repräsentation des angegebenen 32-Bit-Ganzzahlwerts in den Stream. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Schreibt die String-Repräsentation des angegebenen 64-Bit-Ganzzahlwerts in den Stream. |
| virtual void [Write](../textwriter/write/)(**float**) | Schreibt die String-Repräsentation des angegebenen single-Präzisions-Gleitkommawerts in den Stream. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Schreibt die String-Repräsentation des angegebenen unsigned-32-Bit-Ganzzahlwerts in den Stream. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Schreibt die String-Repräsentation des angegebenen unsigned-64-Bit-Ganzzahlwerts in den Stream. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Schreibt die String-Repräsentation des angegebenen [TypeInfo](../../system/typeinfo/)-Objekts in den Stream. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Schreibt die angegebenen Werte, formatiert nach dem angegebenen Format, in den Stream. |
| void [WriteLine](./writeline/)() override | Schreibt Zeilenabschluss-Zeichen in den Stream. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Schreibt die angegebene Zeichenkette, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Schreibt die String-Repräsentation des angegebenen Objekts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Schreibt alle Zeichen des angegebenen Arrays, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Schreibt den angegebenen Teilbereich von UTF-16-Zeichen des angegebenen Zeichenarrays, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| void [WriteLine](./writeline/)(const char_t *) override | Schreibt die angegebene C-String, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Schreibt die String-Repräsentation des angegebenen Objekts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Schreibt die String-Repräsentation des angegebenen booleschen Werts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Schreibt das angegebene Zeichen, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Schreibt die String-Repräsentation des angegebenen [Decimal](../../system/decimal/)-Objekts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Schreibt die String-Repräsentation des angegebenen double-Präzisions-Gleitkommawerts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Schreibt die String-Repräsentation des angegebenen 32-Bit-Ganzzahlwerts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Schreibt die String-Repräsentation des angegebenen 64-Bit-Ganzzahlwerts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Schreibt die String-Repräsentation des angegebenen single-Präzisions-Gleitkommawerts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Schreibt die String-Repräsentation des angegebenen unsigned-32-Bit-Ganzzahlwerts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Schreibt die String-Repräsentation des angegebenen unsigned-64-Bit-Ganzzahlwerts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Schreibt die String-Repräsentation des angegebenen [TypeInfo](../../system/typeinfo/)-Objekts, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Schreibt die angegebenen Werte, formatiert nach dem angegebenen Format, gefolgt von den Zeilenabschluss-Zeichen, in den Stream. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| [~StreamWriter](./~streamwriter/)() | Destruktor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Siehe auch

* Klasse [TextWriter](../textwriter/)
* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)