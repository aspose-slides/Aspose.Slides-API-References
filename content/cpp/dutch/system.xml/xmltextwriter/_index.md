---
title: XmlTextWriter
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een writer voor die een snelle, niet-gebufferde, alleen-voorwaartse manier biedt om streams of bestanden te genereren die XML-gegevens bevatten die voldoen aan de W3C Extensible Markup Language (XML) 1.0 en de Namespaces in XML-aanbevelingen.
type: docs
weight: 521
url: /nl/system.xml/xmltextwriter/
---
## XmlTextWriter klasse

Stelt een writer voor die een snelle, niet-gebufferde, alleen-voorwaartse manier biedt om streams of bestanden te genereren die XML-gegevens bevatten die voldoen aan de W3C Extensible Markup Language (XML) 1.0 en de Namespaces in XML-aanbevelingen.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Close](./close/)() override | Sluit deze stream en de onderliggende stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met de opgegeven bestandsnaam. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met de bestandsnaam en het [XmlWriterSettings](../xmlwritersettings/)-object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met de opgegeven stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met de stream en het [XmlWriterSettings](../xmlwritersettings/)-object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met de opgegeven TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met de TextWriter en de [XmlWriterSettings](../xmlwritersettings/)-objecten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met het opgegeven [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met de [Text::StringBuilder](../../system.text/stringbuilder/)- en [XmlWriterSettings](../xmlwritersettings/)-objecten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met het opgegeven [XmlWriter](../xmlwriter/)-object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Maakt een nieuw [XmlWriter](../xmlwriter/)-instance met de opgegeven [XmlWriter](../xmlwriter/)- en [XmlWriterSettings](../xmlwritersettings/)-objecten. |
| void [Dispose](../xmlwriter/dispose/)() override | Vrijgeeft alle bronnen die door de huidige instantie van de [XmlWriter](../xmlwriter/)-klasse worden gebruikt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetal vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetal vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| void [Flush](./flush/)() override | Leegt de buffer naar de onderliggende streams en leegt tevens de onderliggende stream. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Retourneert het onderliggende stream-object. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Geeft aan hoe de output wordt geformatteerd. |
| **int32_t** [get_Indentation](./get_indentation/)() | Retourneert hoeveel IndentChars er per niveau in de hiërarchie moeten worden geschreven wanneer [XmlTextWriter::set_Formatting](./set_formatting/) is ingesteld op [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Retourneert welk teken moet worden gebruikt voor inspringen wanneer [XmlTextWriter::set_Formatting](./set_formatting/) is ingesteld op [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Retourneert een waarde die aangeeft of namespace-ondersteuning moet worden uitgevoerd. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Retourneert welk teken moet worden gebruikt om attribuutwaarden te citeren. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Retourneert het [XmlWriterSettings](../xmlwritersettings/)-object dat wordt gebruikt om deze [XmlWriter](../xmlwriter/)-instance te maken. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Retourneert de status van de writer. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Retourneert de huidige **xml:lang**-scope. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Retourneert een XmlSpace die de huidige **xml:space**-scope vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt het hashen van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement locken. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Retourneert het dichtstbijzijnde prefix dat is gedefinieerd in de huidige namespace-scope voor de namespace-URI. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt het klonen van aangepaste types in. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Geeft aan hoe de output wordt geformatteerd. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Stelt in hoeveel IndentChars er per niveau in de hiërarchie moeten worden geschreven wanneer [XmlTextWriter::set_Formatting](./set_formatting/) is ingesteld op [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Stelt in welk teken moet worden gebruikt voor inspringen wanneer [XmlTextWriter::set_Formatting](./set_formatting/) is ingesteld op [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Stelt een waarde in die aangeeft of namespace-ondersteuning moet worden uitgevoerd. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Stelt in welk teken moet worden gebruikt om attribuutwaarden te citeren. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt het converteren van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement unlocken. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Wanneer overschreven in een afgeleide klasse, schrijft alle attributen die zich op de huidige positie in de [XmlReader](../xmlreader/) bevinden. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft een attribuut met de opgegeven lokale naam, namespace-URI en waarde. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft het attribuut met de opgegeven lokale naam en waarde. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft het attribuut met het opgegeven prefix, lokale naam, namespace-URI en waarde. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Encodeert de opgegeven binaire bytes als base64 en schrijft de resulterende tekst. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Encodeert de opgegeven binaire bytes als binhex en schrijft de resulterende tekst. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Schrijft een **...**-blok met de opgegeven tekst. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Forceert de generatie van een tekentegoed voor de opgegeven Unicode-tekenwaarde. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Schrijft tekst buffer per buffer. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Schrijft een commentaar **** met de opgegeven tekst. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Schrijft de DOCTYPE-declaratie met de opgegeven naam en optionele attributen. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft een element met de opgegeven lokale naam en waarde. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft een element met de opgegeven lokale naam, namespace-URI en waarde. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft een element met het opgegeven prefix, lokale naam, namespace-URI en waarde. |
| void [WriteEndAttribute](./writeendattribute/)() override | Sluit de vorige [XmlTextWriter::WriteStartAttribute](./writestartattribute/)-aanroep. |
| void [WriteEndDocument](./writeenddocument/)() override | Sluit alle geopende elementen of attributen en zet de writer terug in de Start-status. |
| void [WriteEndElement](./writeendelement/)() override | Sluit één element en verwijdert de bijbehorende namespace-scope. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Schrijft een entiteit-referentie als **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Sluit één element en verwijdert de bijbehorende namespace-scope. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Schrijft de opgegeven naam, en zorgt dat deze een geldige naam is volgens de [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Schrijft de opgegeven naam, en zorgt dat deze een geldig **NmToken** is volgens de [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Wanneer overschreven in een afgeleide klasse, kopieert alles van de reader naar de writer en verplaatst de reader naar het begin van de volgende sibling. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Kopieert alles van het XPathNavigator-object naar de writer. De positie van de XPathNavigator blijft ongewijzigd. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Schrijft een verwerkingsinstructie met een spatie tussen de naam en tekst als volgt: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Schrijft de namespace-gekwalificeerde naam. Deze methode zoekt het prefix op dat in scope is voor de opgegeven namespace. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Schrijft ruwe markup handmatig vanuit een tekenbuffer. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Schrijft ruwe markup handmatig vanuit een string. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Schrijft het begin van een attribuut. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft het begin van een attribuut met de opgegeven lokale naam en namespace-URI. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Schrijft het begin van een attribuut met de opgegeven lokale naam. |
| void [WriteStartDocument](./writestartdocument/)() override | Schrijft de XML-declaratie met versie "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Schrijft de XML-declaratie met versie "1.0" en het standalone-attribuut. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Schrijft de opgegeven start-tag en koppelt deze aan de gegeven namespace en prefix. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft de opgegeven start-tag en koppelt deze aan de gegeven namespace. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft een start-tag met de opgegeven lokale naam. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Schrijft de opgegeven tekstinhoud. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Genereert en schrijft de surrogate-teken-entity voor het surrogate-tekenpaar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Schrijft de objectwaarde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Schrijft een [String](../../system/string/)-waarde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Schrijft een [Boolean](../../system/boolean/)-waarde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Schrijft een [DateTime](../../system/datetime/)-waarde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Schrijft een [DateTimeOffset](../../system/datetimeoffset/)-waarde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Schrijft een [Double](../../system/double/)-waarde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Schrijft een enkelprecisie zwevend-kommagetal. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Schrijft een [Decimal](../../system/decimal/)-waarde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Schrijft een [Int32](../../system/int32/)-waarde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Schrijft een [Int64](../../system/int64/)-waarde. |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Schrijft de opgegeven witruimte. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Creëert een instantie van de [XmlTextWriter](./)-klasse met de opgegeven stream en codering. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Creëert een instantie van de [XmlTextWriter](./)-klasse met het opgegeven bestand. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Creëert een instantie van de [XmlTextWriter](./)-klasse met de opgegeven TextWriter. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne datastructuren. |

## Type-definities

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |

## Opmerkingen

Het wordt aanbevolen om in plaats daarvan de [XmlWriter](../xmlwriter/)-klasse te gebruiken.

Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assert-fouten oplevert. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om deze door te geven aan functies als argument.

## Zie ook

* Klasse [XmlWriter](../xmlwriter/)
* Naamruimte [System::Xml](../)
* Library [Aspose.Slides](../../)