---
title: StreamReader
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt einen Leser dar, der Zeichen aus einem Bytestrom liest. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 378
url: /de/system.io/streamreader/
---
## StreamReader Klasse


Stellt einen Leser dar, der Zeichen aus einem Bytestrom liest. Objekte dieser Klasse sollten nur mithilfe der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class StreamReader : public System::IO::TextReader
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Close](./close/)() override | Schließt den aktuellen und den zugrunde liegenden Strom. |
| virtual void [Dispose](./dispose/)(**bool**) | Gibt alle vom aktuellen Objekt verwendeten Ressourcen frei und schließt den zugrunde liegenden Strom. |
| void [Dispose](./dispose/)() override | Gibt alle vom aktuellen Objekt verwendeten Ressourcen frei und schließt den zugrunde liegenden Strom. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C# Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C# Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-style Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-style Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Gibt einen Shared-Pointer auf ein Objekt zurück, das den zugrunde liegenden Strom repräsentiert. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Gibt die derzeit verwendete Kodierung zurück. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Gibt einen Wert zurück, der anzeigt, ob das Ende des Stroms erreicht wurde. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C# 'is' Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Rufen Sie es direkt auf oder verwenden Sie das [LockContext](../../system/lockcontext/) Wachobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Subklassen. |
| int [Peek](./peek/)() override | Liest ein einzelnes Zeichen aus dem Strom, ohne den Leseposition des Stroms zu verändern. |
| int [Read](./read/)() override | Liest ein einzelnes Zeichen aus dem Strom. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Liest die angegebene Anzahl von Zeichen aus dem Strom, konvertiert sie in die UTF-16 Kodierung und schreibt die resultierenden UTF-16 Zeichen in das angegebene Zeichenarray beginnend an der angegebenen Position. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Liest die angegebene maximale Anzahl von Zeichen aus dem aktuellen Textleser und schreibt die Daten in einen Puffer, beginnend am angegebenen Index. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Liest Zeichen aus dem Strom bis zum Ende der aktuellen Zeile. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Liest Zeichen aus dem Strom bis zum Ende des Stroms. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz einen Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n'te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus dem angegebenen zugrunde liegenden Strom mit UTF-8 Kodierung und einem Puffer der Standardgröße von 1024 Bytes liest. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus dem angegebenen zugrunde liegenden Strom mit UTF-8 Kodierung und einem Puffer der Standardgröße von 1024 Bytes liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Mark aktiviert werden soll. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus dem angegebenen zugrunde liegenden Strom mit der angegebenen Kodierung und einem Puffer der Standardgröße von 1024 Bytes liest. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus dem angegebenen zugrunde liegenden Strom mit der angegebenen Kodierung und einem Puffer der Standardgröße von 1024 Bytes liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Mark aktiviert werden soll. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus dem angegebenen zugrunde liegenden Strom mit der angegebenen Kodierung und einem Puffer der angegebenen Größe liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Mark aktiviert werden soll. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus der angegebenen Datei mit UTF-8 Kodierung und einem Puffer der Standardgröße von 4096 Bytes liest. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus der angegebenen Datei mit UTF-8 Kodierung und einem Puffer der Standardgröße von 4096 Bytes liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Mark aktiviert werden soll. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus der angegebenen Datei mit der angegebenen Kodierung und einem Puffer der Standardgröße von 4096 Bytes liest. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus dem angegebenen zugrunde liegenden Strom mit der angegebenen Kodierung und einem Puffer der Standardgröße von 4096 Bytes liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Mark aktiviert werden soll. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Konstruiert eine Instanz des [StreamReader](./) Objekts, das Zeichen aus der angegebenen Datei mit der angegebenen Kodierung und einem Puffer der angegebenen Größe liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Mark aktiviert werden soll. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/)) Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Rufen Sie es direkt auf oder verwenden Sie das [LockContext](../../system/lockcontext/) Wachobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
|  [~StreamReader](./~streamreader/)() | Destruktor. |
## Siehe auch

* Klasse [TextReader](../textreader/)
* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)