---
title: XmlWriter
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Writer dar, der eine schnelle, nicht zwischengespeicherte, nur vorwärts gerichtete Methode zum Erzeugen von Streams oder Dateien bietet, die XML-Daten enthalten.
type: docs
weight: 573
url: /de/system.xml/xmlwriter/
---
## XmlWriter Klasse

Stellt einen Writer dar, der eine schnelle, nicht zwischengespeicherte, nur vorwärts gerichtete Methode zum Erzeugen von Streams oder Dateien bereitstellt, die XML-Daten enthalten.

```cpp
class XmlWriter : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [Close](./close/)() | Wenn in einer abgeleiteten Klasse überschrieben, schließt diesen Stream und den zugrunde liegenden Stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Erstellt eine neue [XmlWriter](./)-Instanz mit dem angegebenen Dateinamen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](./)-Instanz mit dem Dateinamen und dem [XmlWriterSettings](../xmlwritersettings/)-Objekt. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Erstellt eine neue [XmlWriter](./)-Instanz mit dem angegebenen Stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](./)-Instanz mit dem Stream und dem [XmlWriterSettings](../xmlwritersettings/)-Objekt. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Erstellt eine neue [XmlWriter](./)-Instanz mit dem angegebenen TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](./)-Instanz mit dem TextWriter und den [XmlWriterSettings](../xmlwritersettings/)-Objekten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Erstellt eine neue [XmlWriter](./)-Instanz mit dem angegebenen [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](./)-Instanz mit den [Text::StringBuilder](../../system.text/stringbuilder/)- und [XmlWriterSettings](../xmlwritersettings/)-Objekten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Erstellt eine neue [XmlWriter](./)-Instanz mit dem angegebenen [XmlWriter](./)-Objekt. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](./)-Instanz mit den angegebenen [XmlWriter](./)- und [XmlWriterSettings](../xmlwritersettings/)-Objekten. |
| void [Dispose](./dispose/)() override | Gibt alle von der aktuellen Instanz der [XmlWriter](./)-Klasse verwendeten Ressourcen frei. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN keinem Wert, inklusive NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN keinem Wert, inklusive NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual void [Flush](./flush/)() | Wenn in einer abgeleiteten Klasse überschrieben, wird der Puffer in die zugrunde liegenden Streams geleert und auch der zugrunde liegende Stream geflusht. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Gibt das [XmlWriterSettings](../xmlwritersettings/)-Objekt zurück, das zur Erstellung dieser [XmlWriter](./)-Instanz verwendet wurde. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Wenn in einer abgeleiteten Klasse überschrieben, holt den Zustand des Writers. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Wenn in einer abgeleiteten Klasse überschrieben, holt den aktuellen **xml:lang**-Geltungsbereich. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Wenn in einer abgeleiteten Klasse überschrieben, holt ein XmlSpace, das den aktuellen **xml:space**-Geltungsbereich darstellt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die mit dem Objekt verbundene Referenzzähler-Datenstruktur zurück. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Wenn in einer abgeleiteten Klasse überschrieben, gibt das dem Namespace-URI am nächsten stehende Präfix im aktuellen Namensraum-Geltungsbereich zurück. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Subklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt alle Attribute, die an der aktuellen Position im [XmlReader](../xmlreader/) gefunden wurden, aus. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt ein Attribut mit dem angegebenen lokalen Namen, Namespace-URI und Wert. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt das Attribut mit dem angegebenen lokalen Namen und Wert. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt das Attribut mit dem angegebenen Präfix, lokalen Namen, Namespace-URI und Wert. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Wenn in einer abgeleiteten Klasse überschrieben, kodiert die angegebenen Binärbytes als Base64 und schreibt den resultierenden Text. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Wenn in einer abgeleiteten Klasse überschrieben, kodiert die angegebenen Binärbytes als **BinHex** und schreibt den resultierenden Text. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt einen **...**-Block mit dem angegebenen Text. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Wenn in einer abgeleiteten Klasse überschrieben, erzwingt die Erzeugung einer Zeichenentität für den angegebenen Unicode-Zeichenwert. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt Text Puffer für Puffer. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt einen Kommentar **** mit dem angegebenen Text. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt die DOCTYPE-Deklaration mit dem angegebenen Namen und optionalen Attributen. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt ein Element mit dem angegebenen lokalen Namen und Wert. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt ein Element mit dem angegebenen lokalen Namen, Namespace-URI und Wert. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt ein Element mit dem angegebenen Präfix, lokalen Namen, Namespace-URI und Wert. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Wenn in einer abgeleiteten Klasse überschrieben, schließt den vorherigen Aufruf von XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | Wenn in einer abgeleiteten Klasse überschrieben, schließt alle offenen Elemente oder Attribute und setzt den Writer zurück in den Start-Zustand. |
| virtual void [WriteEndElement](./writeendelement/)() | Wenn in einer abgeleiteten Klasse überschrieben, schließt ein Element und entfernt den zugehörigen Namensraum-Geltungsbereich. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt eine Entity-Referenz als **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Wenn in einer abgeleiteten Klasse überschrieben, schließt ein Element und entfernt den zugehörigen Namensraum-Geltungsbereich. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt den angegebenen Namen und stellt sicher, dass er gemäß der W3C XML 1.0-Empfehlung ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) ein gültiger Name ist. |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt den angegebenen Namen und stellt sicher, dass er gemäß der W3C XML 1.0-Empfehlung ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) ein gültiges NmToken ist. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Wenn in einer abgeleiteten Klasse überschrieben, kopiert alles vom Reader zum Writer und bewegt den Reader an den Anfang des nächsten Geschwisterelements. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Kopiert alles vom XPathNavigator-Objekt zum Writer. Die Position des XPathNavigator bleibt unverändert. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt eine Verarbeitungsanweisung mit einem Leerzeichen zwischen Name und Text, z.B. **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt den namespace-qualifizierten Namen. Diese Methode ermittelt das im Geltungsbereich für den angegebenen Namespace gültige Präfix. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt rohes Markup manuell aus einem Zeichenpuffer. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt rohes Markup manuell aus einem String. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt den Beginn eines Attributs mit dem angegebenen lokalen Namen und Namespace-URI. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt den Beginn eines Attributs mit dem angegebenen Präfix, lokalen Namen und Namespace-URI. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Schreibt den Beginn eines Attributs mit dem angegebenen lokalen Namen. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Wenn in einer abgeleiteten Klasse überschrieben, schreibt die XML-Deklaration mit der Version "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt die XML-Deklaration mit der Version "1.0" und dem Attribut standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt das angegebene Start-Tag und verknüpft es mit dem gegebenen Namespace. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt das angegebene Start-Tag und verknüpft es mit dem gegebenen Namespace und Präfix. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt ein Start-Tag mit dem angegebenen lokalen Namen. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt den angegebenen Textinhalt. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Wenn in einer abgeleiteten Klasse überschrieben, erzeugt und schreibt die Surrogat-Zeichenentität für das Surrogat-Zeichenpaar. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Schreibt den Objektwert. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Schreibt einen [String](../../system/string/)-Wert. |
| virtual void [WriteValue](./writevalue/)(**bool**) | Schreibt einen [Boolean](../../system/boolean/)-Wert. |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Schreibt einen [DateTime](../../system/datetime/)-Wert. |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Schreibt einen [DateTimeOffset](../../system/datetimeoffset/)-Wert. |
| virtual void [WriteValue](./writevalue/)(**double**) | Schreibt einen [Double](../../system/double/)-Wert. |
| virtual void [WriteValue](./writevalue/)(**float**) | Schreibt eine Gleitkommazahl mit einfacher Genauigkeit. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Schreibt einen [Decimal](../../system/decimal/)-Wert. |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Schreibt einen [Int32](../../system/int32/)-Wert. |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Schreibt einen [Int64](../../system/int64/)-Wert. |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt das angegebene Leerzeichen. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |

## Siehe Auch

* Klasse [IDisposable](../../system/idisposable/)
* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)