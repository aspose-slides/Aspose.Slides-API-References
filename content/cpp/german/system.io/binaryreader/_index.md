---
title: BinaryReader
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Reader dar, der primitive Datentypen als Binärdaten in einer bestimmten Kodierung liest. Objekte dieser Klasse sollten ausschließlich mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 92
url: /de/system.io/binaryreader/
---
## BinaryReader Klasse


Repäsentiert einen Reader, der primitive Datentypen als Binärdaten in einer bestimmten Kodierung liest. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/) Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class BinaryReader : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Konstruiert eine Instanz der [BinaryReader](./) Klasse, die Daten aus dem angegebenen Stream mit UTF-8-Kodierung liest. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Konstruiert eine Instanz der [BinaryReader](./) Klasse, die Daten aus dem angegebenen Stream mit der angegebenen Kodierung liest. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Konstruiert eine Instanz der [BinaryReader](./) Klasse, die Daten aus dem angegebenen Stream mit der angegebenen Kodierung liest. |
| virtual void [Close](./close/)() | Schließt das aktuelle [BinaryReader](./) Objekt und den zugrunde liegenden Eingabestream. |
| void [Dispose](./dispose/)() override | Gibt alle vom aktuellen Objekt genutzten Ressourcen frei und schließt den zugrunde liegenden Stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mithilfe der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich angesehen werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich angesehen werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Gibt den Eingabestream zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächter-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| virtual int [PeekChar](./peekchar/)() | Liest ein einzelnes Zeichen aus dem Eingabestream, ohne den Lesecursor des Streams zu verändern. |
| virtual int [Read](./read/)() | Liest ein einzelnes Zeichen aus dem Eingabestream. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Liest die angegebene Anzahl von Bytes aus dem Eingabestream und schreibt sie in das angegebene Byte-Array. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Liest die angegebene Anzahl von Zeichen aus dem Eingabestream, wandelt sie in UTF-16-Kodierung um und schreibt die resultierenden UTF-16-Zeichen in das angegebene Zeichenarray, beginnend an der angegebenen Position. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Liest ein einzelnes Byte aus dem Eingabestream und gibt dessen boolesche Darstellung zurück. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Liest ein einzelnes Byte aus dem Eingabestream. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Liest die angegebene Anzahl von Bytes aus dem Eingabestream. |
| virtual char_t [ReadChar](./readchar/)() | Liest ein einzelnes Zeichen aus dem Eingabestream. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Liest die angegebene Anzahl von Zeichen aus dem Eingabestream und gibt sie in UTF-16-Kodierung zurück. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | NICHT IMPLEMENTIERT. |
| virtual **double** [ReadDouble](./readdouble/)() | Liest 8 Bytes aus dem Eingabestream und gibt sie als double-Präzisions-Gleitkommawert zurück. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Liest 2 Bytes aus dem Eingabestream und gibt sie als 16-Bit-Ganzzahlwert zurück. |
| virtual int [ReadInt32](./readint32/)() | Liest 4 Bytes aus dem Eingabestream und gibt sie als 32-Bit-Ganzzahlwert zurück. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Liest 8 Bytes aus dem Eingabestream und gibt sie als 64-Bit-Ganzzahlwert zurück. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Liest ein einzelnes Byte aus dem Eingabestream und gibt es als vorzeichenbehafteten 8-Bit-Ganzzahlwert zurück. |
| virtual **float** [ReadSingle](./readsingle/)() | Liest 4 Bytes aus dem Eingabestream und gibt sie als single-Präzisions-Gleitkommawert zurück. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Liest einen String aus dem aktuellen Stream. Der String wird mit der Länge vorangestellt, die als Integer in 7-Bit-Blöcken kodiert ist. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Liest 2 Bytes aus dem Eingabestream und gibt sie als vorzeichenlosen 16-Bit-Ganzzahlwert zurück. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Liest 4 Bytes aus dem Eingabestream und gibt sie als vorzeichenlosen 32-Bit-Ganzzahlwert zurück. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Liest 8 Bytes aus dem Eingabestream und gibt sie als vorzeichenlosen 64-Bit-Ganzzahlwert zurück. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt einem geteilten). Erlaubt das Wechseln von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/)) Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächter-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~BinaryReader](./~binaryreader/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IDisposable](../../system/idisposable/)
* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)