---
title: XmlTextWriter
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Writer dar, der eine schnelle, nicht gepufferte, vorwärts-nur-Lese-Möglichkeit zum Erzeugen von Streams oder Dateien mit XML-Daten bietet, die den W3C Extensible Markup Language (XML) 1.0 und den Empfehlungen für Namespaces in XML entsprechen.
type: docs
weight: 521
url: /de/system.xml/xmltextwriter/
---
## XmlTextWriter Klasse

Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Close](./close/)() override | Schließt diesen Stream und den zugrunde liegenden Stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung des angegebenen Dateinamens. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung des Dateinamens und des [XmlWriterSettings](../xmlwritersettings/)-Objekts. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung des angegebenen Streams. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung des Streams und des [XmlWriterSettings](../xmlwritersettings/)-Objekts. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung des angegebenen TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung des TextWriter und der [XmlWriterSettings](../xmlwritersettings/)-Objekte. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung des angegebenen [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung der [Text::StringBuilder](../../system.text/stringbuilder/)- und [XmlWriterSettings](../xmlwritersettings/)-Objekte. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung des angegebenen [XmlWriter](../xmlwriter/)-Objekts. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Erstellt eine neue [XmlWriter](../xmlwriter/)-Instanz unter Verwendung der angegebenen [XmlWriter](../xmlwriter/)- und [XmlWriterSettings](../xmlwritersettings/)-Objekte. |
| void [Dispose](../xmlwriter/dispose/)() override | Gibt alle von der aktuellen Instanz der [XmlWriter](../xmlwriter/)-Klasse verwendeten Ressourcen frei. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| void [Flush](./flush/)() override | Spült alles, was im Puffer ist, zu den zugrunde liegenden Streams und spült außerdem den zugrunde liegenden Stream. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Gibt das zugrunde liegende Stream-Objekt zurück. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Gibt an, wie die Ausgabe formatiert ist. |
| **int32_t** [get_Indentation](./get_indentation/)() | Gibt zurück, wie viele IndentChars für jede Ebene in der Hierarchie geschrieben werden sollen, wenn [XmlTextWriter::set_Formatting](./set_formatting/) auf [Formatting::Indented](../formatting/) gesetzt ist. |
| char16_t [get_IndentChar](./get_indentchar/)() | Gibt zurück, welches Zeichen für Einrückungen verwendet wird, wenn [XmlTextWriter::set_Formatting](./set_formatting/) auf [Formatting::Indented](../formatting/) gesetzt ist. |
| **bool** [get_Namespaces](./get_namespaces/)() | Gibt einen Wert zurück, der angibt, ob Namespace-Unterstützung verwendet werden soll. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Gibt zurück, welches Zeichen zum Zitieren von Attributwerten verwendet wird. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Gibt das [XmlWriterSettings](../xmlwritersettings/)-Objekt zurück, das zur Erstellung dieser [XmlWriter](../xmlwriter/)-Instanz verwendet wurde. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Gibt den Zustand des Writers zurück. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Gibt den aktuellen **xml:lang**-Geltungsbereich zurück. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Gibt einen XmlSpace zurück, der den aktuellen **xml:space**-Geltungsbereich darstellt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Gibt das nächstgelegene Präfix zurück, das im aktuellen Namespace-Geltungsbereich für die Namespace-URI definiert ist. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzähler um den angegebenen Wert. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Gibt an, wie die Ausgabe formatiert ist. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Legt fest, wie viele IndentChars für jede Ebene in der Hierarchie geschrieben werden sollen, wenn [XmlTextWriter::set_Formatting](./set_formatting/) auf [Formatting::Indented](../formatting/) gesetzt ist. |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Legt fest, welches Zeichen für Einrückungen verwendet wird, wenn [XmlTextWriter::set_Formatting](./set_formatting/) auf [Formatting::Indented](../formatting/) gesetzt ist. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Legt einen Wert fest, der angibt, ob Namespace-Unterstützung verwendet werden soll. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Legt fest, welches Zeichen zum Zitieren von Attributwerten verwendet wird. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines Shared-Pointers). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt alle Attribute, die an der aktuellen Position im [XmlReader](../xmlreader/) gefunden werden, aus. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt ein Attribut mit dem angegebenen lokalen Namen, der Namespace-URI und dem Wert. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt das Attribut mit dem angegebenen lokalen Namen und Wert aus. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt das Attribut mit dem angegebenen Präfix, lokalen Namen, Namespace-URI und Wert aus. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Kodiert die angegebenen Binärbytes als Base64 und schreibt den resultierenden Text. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Kodiert die angegebenen Binärbytes als Binhex und schreibt den resultierenden Text. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Schreibt einen **...**-Block, der den angegebenen Text enthält. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Erzwingt die Erzeugung einer Zeichen-Entität für den angegebenen Unicode-Zeichenwert. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Schreibt Text jeweils einen Puffer auf einmal. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Schreibt einen Kommentar ****, der den angegebenen Text enthält. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Schreibt die DOCTYPE-Deklaration mit dem angegebenen Namen und optionalen Attributen. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt ein Element mit dem angegebenen lokalen Namen und Wert. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt ein Element mit dem angegebenen lokalen Namen, der Namespace-URI und dem Wert. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt ein Element mit dem angegebenen Präfix, lokalen Namen, Namespace-URI und Wert. |
| void [WriteEndAttribute](./writeendattribute/)() override | Schließt den vorherigen [XmlTextWriter::WriteStartAttribute](./writestartattribute/)-Aufruf. |
| void [WriteEndDocument](./writeenddocument/)() override | Schließt alle offenen Elemente oder Attribute und versetzt den Writer zurück in den Start-Zustand. |
| void [WriteEndElement](./writeendelement/)() override | Schließt ein Element und entfernt den entsprechenden Namespace-Geltungsbereich. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Schreibt eine Entity-Referenz als **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Schließt ein Element und entfernt den entsprechenden Namespace-Geltungsbereich. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Schreibt den angegebenen Namen, wobei sichergestellt wird, dass er gemäß [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) ein gültiger Name ist. |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Schreibt den angegebenen Namen, wobei sichergestellt wird, dass er gemäß [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) ein gültiges **NmToken** ist. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Wenn in einer abgeleiteten Klasse überschrieben, kopiert alles vom Reader zum Writer und verschiebt den Reader an den Anfang des nächsten Geschwisterelements. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Kopiert alles vom XPathNavigator-Objekt zum Writer. Die Position des XPathNavigator bleibt unverändert. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Schreibt eine Verarbeitungsanweisung mit einem Leerzeichen zwischen Name und Text, wie folgt: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Schreibt den namespace-qualifizierten Namen aus. Diese Methode ermittelt das im Geltungsbereich für den angegebenen Namespace vorhandene Präfix. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Schreibt rohes Markup manuell aus einem Zeichenpuffer. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Schreibt rohes Markup manuell aus einem String. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Schreibt den Beginn eines Attributs. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt den Beginn eines Attributs mit dem angegebenen lokalen Namen und der Namespace-URI. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Schreibt den Beginn eines Attributs mit dem angegebenen lokalen Namen. |
| void [WriteStartDocument](./writestartdocument/)() override | Schreibt die XML-Deklaration mit der Version "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Schreibt die XML-Deklaration mit der Version "1.0" und dem Standalone-Attribut. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Schreibt das angegebene Start-Tag und verbindet es mit dem angegebenen Namespace und Präfix. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt das angegebene Start-Tag und verbindet es mit dem angegebenen Namespace. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt ein Start-Tag mit dem angegebenen lokalen Namen. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Schreibt den angegebenen Textinhalt. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Erzeugt und schreibt die Surrogate-Zeichen-Entität für das Surrogate-Zeichenpaar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Schreibt den Objektwert. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Schreibt einen [String](../../system/string/)-Wert. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Schreibt einen [Boolean](../../system/boolean/)-Wert. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Schreibt einen [DateTime](../../system/datetime/)-Wert. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Schreibt einen [DateTimeOffset](../../system/datetimeoffset/)-Wert. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Schreibt einen [Double](../../system/double/)-Wert. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Schreibt eine Gleitkommazahl in einfacher Genauigkeit. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Schreibt einen [Decimal](../../system/decimal/)-Wert. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Schreibt einen [Int32](../../system/int32/)-Wert. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Schreibt einen [Int64](../../system/int64/)-Wert. |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Schreibt das angegebene Leerzeichen. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Erstellt eine Instanz der [XmlTextWriter](./)-Klasse unter Verwendung des angegebenen Streams und der Kodierung. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Erstellt eine Instanz der [XmlTextWriter](./)-Klasse unter Verwendung der angegebenen Datei. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Erstellt eine Instanz der [XmlTextWriter](./)-Klasse unter Verwendung des angegebenen TextWriter. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |

## Bemerkungen

Es wird empfohlen, stattdessen die [XmlWriter](../xmlwriter/)-Klasse zu verwenden.

Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziiert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Klasse [XmlWriter](../xmlwriter/)
* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)