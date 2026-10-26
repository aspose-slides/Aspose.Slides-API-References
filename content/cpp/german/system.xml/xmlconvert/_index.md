---
title: XmlConvert
second_title: Aspose.Slides für C++ API-Referenz
description: Kodiert und dekodiert XML-Namen und stellt Methoden zum Konvertieren zwischen Laufzeittypen und XML-Schema-Definitionssprache (XSD)-Typen bereit. Beim Konvertieren von Datentypen sind die zurückgegebenen Werte sprachunabhängig.
type: docs
weight: 157
url: /de/system.xml/xmlconvert/
---
## XmlConvert Klasse

Kodiert und dekodiert XML-Namen und bietet Methoden zum Konvertieren zwischen Laufzeittypen und XML [Schema](../../system.xml.schema/)-Definitionssprache (XSD)-Typen. Beim Konvertieren von Datentypen sind die zurückgegebenen Werte sprachunabhängig.

```cpp
class XmlConvert : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Dekodiert einen Namen. Diese Methode führt das Gegenteil der Methoden XmlConvert::EncodeName(String) und XmlConvert::EncodeLocalName(String) aus. |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Konvertiert den Namen in einen gültigen XML-Lokalnamen. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Konvertiert den Namen in einen gültigen XML-Namen. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Überprüft, ob der Name gemäß der XML-Spezifikation gültig ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Überprüft, ob das übergebene Zeichen ein gültiger Nicht-Doppelpunkt-Zeichentyp ist. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Gibt das übergebene Zeichen zurück, wenn das Zeichen im Argument ein gültiges public-id-Zeichen ist, andernfalls **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Überprüft, ob das übergebene Zeichen ein gültiger Start-Name-Zeichen-Typ ist. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Überprüft, ob das übergebene Zeichen ein gültiges XML-Whitespace-Zeichen ist. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Überprüft, ob das übergebene Zeichen ein gültiges XML-Zeichen ist. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Überprüft, ob das übergebene Surrogat-Paar von Zeichen ein gültiges XML-Zeichen ist. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sicherheitsobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Konvertiert [String](../../system/string/) in ein äquivalentes [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Konvertiert [String](../../system/string/) in ein [DateTime](../../system/datetime/) unter Verwendung des angegebenen XmlDateTimeSerializationMode. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Konvertiert das bereitgestellte [String](../../system/string/) in ein äquivalentes [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konvertiert das bereitgestellte [String](../../system/string/) in ein äquivalentes [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Konvertiert das bereitgestellte [String](../../system/string/) in ein äquivalentes [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Konvertiert [String](../../system/string/) in ein äquivalentes [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Konvertiert [String](../../system/string/) in ein äquivalentes [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Konvertiert [Boolean](../../system/boolean/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Konvertiert [Char](../../system/char/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Konvertiert [Decimal](../../system/decimal/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Konvertiert [SByte](../../system/sbyte/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Konvertiert [Int16](../../system/int16/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Konvertiert [Int32](../../system/int32/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Konvertiert [Int64](../../system/int64/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Konvertiert [Byte](../../system/byte/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Konvertiert [UInt16](../../system/uint16/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Konvertiert [UInt32](../../system/uint32/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Konvertiert [UInt64](../../system/uint64/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Konvertiert [Single](../../system/single/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Konvertiert [Double](../../system/double/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Konvertiert [TimeSpan](../../system/timespan/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Konvertiert [DateTime](../../system/datetime/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Konvertiert [DateTime](../../system/datetime/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Konvertiert [DateTime](../../system/datetime/) in ein [String](../../system/string/) unter Verwendung des angegebenen XmlDateTimeSerializationMode. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Konvertiert das bereitgestellte [DateTimeOffset](../../system/datetimeoffset/) in ein [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Konvertiert das bereitgestellte [DateTimeOffset](../../system/datetimeoffset/) in ein [String](../../system/string/) im angegebenen Format. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Konvertiert [Guid](../../system/guid/) in ein [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Konvertiert [String](../../system/string/) in ein äquivalentes [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sicherheitsobjekt verwenden. |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Überprüft, ob der Name gemäß der W3C Extended Markup Language-Empfehlung ein gültiger Name ist. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Überprüft, ob der Name gemäß der W3C Extended Markup Language-Empfehlung ein gültiger **NCName** ist. Ein **NCName** ist ein Name, der keinen Doppelpunkt enthalten darf. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Überprüft, ob die Zeichenkette gemäß der W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes-Empfehlung ein gültiges NMTOKEN ist. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Gibt die übergebene Zeichenketteninstanz zurück, wenn alle Zeichen im String-Argument gültige public-id-Zeichen sind. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Überprüft, ob die Zeichenkette gemäß der W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes-Empfehlung ein gültiges Token ist. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Gibt die übergebene Zeichenkette zurück, wenn alle Zeichen im String-Argument gültige Whitespace-Zeichen sind. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Gibt die übergebene Zeichenkette zurück, wenn alle Zeichen und Surrogat-Paar-Zeichen im String-Argument gültige XML-Zeichen sind, andernfalls wird eine XmlException mit Informationen über das zuerst ungültige Zeichen ausgelöst. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)