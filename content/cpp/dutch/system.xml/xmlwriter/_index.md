---
title: XmlWriter
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een schrijver die een snelle, niet-gecachede, alleen-voorwaarts manier biedt om streams of bestanden te genereren die XML-gegevens bevatten.
type: docs
weight: 573
url: /nl/system.xml/xmlwriter/
---
## XmlWriter klasse


Representeert een writer die een snelle, niet-gecachede, alleen-voorwaarts manier biedt om streams of bestanden te genereren die XML-gegevens bevatten.

```cpp
class XmlWriter : public System::IDisposable
```

## Methodes

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Wanneer overschreven in een afgeleide klasse, sluit deze stream en de onderliggende stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Creëert een nieuw [XmlWriter](./)-instance met de opgegeven bestandsnaam. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creëert een nieuw [XmlWriter](./)-instance met de bestandsnaam en [XmlWriterSettings](../xmlwritersettings/)-object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Creëert een nieuw [XmlWriter](./)-instance met de opgegeven stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creëert een nieuw [XmlWriter](./)-instance met de stream en [XmlWriterSettings](../xmlwritersettings/)-object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Creëert een nieuw [XmlWriter](./)-instance met de opgegeven TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creëert een nieuw [XmlWriter](./)-instance met de TextWriter en [XmlWriterSettings](../xmlwritersettings/)-objecten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Creëert een nieuw [XmlWriter](./)-instance met de opgegeven [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creëert een nieuw [XmlWriter](./)-instance met de [Text::StringBuilder](../../system.text/stringbuilder/)- en [XmlWriterSettings](../xmlwritersettings/)-objecten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Creëert een nieuw [XmlWriter](./)-instance met het opgegeven [XmlWriter](./)-object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creëert een nieuw [XmlWriter](./)-instance met de opgegeven [XmlWriter](./)- en [XmlWriterSettings](../xmlwritersettings/)-objecten. |
| void [Dispose](./dispose/)() override | Geeft alle resources vrij die door de huidige [XmlWriter](./) klasse-instance worden gebruikt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual void [Flush](./flush/)() | Wanneer overschreven in een afgeleide klasse, flushes wat er in de buffer zit naar de onderliggende streams en flushes tevens de onderliggende stream. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Retourneert het [XmlWriterSettings](../xmlwritersettings/)-object dat wordt gebruikt om deze [XmlWriter](./)-instance te maken. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Wanneer overschreven in een afgeleide klasse, krijgt de status van de writer. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Wanneer overschreven in een afgeleide klasse, krijgt de huidige **xml:lang**-scope. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Wanneer overschreven in een afgeleide klasse, krijgt een XmlSpace die de huidige **xml:space**-scope vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van de C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Wanneer overschreven in een afgeleide klasse, retourneert de dichtstbijzijnde prefix die in de huidige namespace-scope is gedefinieerd voor de namespace-URI. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referentie-vergelijkt waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert de C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Wanneer overschreven in een afgeleide klasse, schrijft alle attributen die zich op de huidige positie in de [XmlReader](../xmlreader/) bevinden. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft een attribuut met de opgegeven lokale naam, namespace-URI en waarde. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft het attribuut met de opgegeven lokale naam en waarde. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft het attribuut met de opgegeven prefix, lokale naam, namespace-URI en waarde. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Wanneer overschreven in een afgeleide klasse, codeert de opgegeven binaire bytes als Base64 en schrijft de resulterende tekst. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Wanneer overschreven in een afgeleide klasse, codeert de opgegeven binaire bytes als **BinHex** en schrijft de resulterende tekst. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Wanneer overschreven in een afgeleide klasse, schrijft een **...**-blok met de opgegeven tekst. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Wanneer overschreven in een afgeleide klasse, forceert de generatie van een character-entity voor de opgegeven Unicode-tekenwaarde. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Wanneer overschreven in een afgeleide klasse, schrijft tekst één buffer per keer. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Wanneer overschreven in een afgeleide klasse, schrijft een commentaar **** met de opgegeven tekst. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft de DOCTYPE-declaratie met de opgegeven naam en optionele attributen. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft een element met de opgegeven lokale naam en waarde. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft een element met de opgegeven lokale naam, namespace-URI en waarde. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft een element met de opgegeven prefix, lokale naam, namespace-URI en waarde. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Wanneer overschreven in een afgeleide klasse, sluit de vorige XmlWriter::WriteStartAttribute(String,String)-aanroep. |
| virtual void [WriteEndDocument](./writeenddocument/)() | Wanneer overschreven in een afgeleide klasse, sluit alle geopende elementen of attributen en plaatst de writer terug in de Start-status. |
| virtual void [WriteEndElement](./writeendelement/)() | Wanneer overschreven in een afgeleide klasse, sluit één element en verwijdert de bijbehorende namespace-scope. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft een entity-referentie als **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Wanneer overschreven in een afgeleide klasse, sluit één element en verwijdert de bijbehorende namespace-scope. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft de opgegeven naam, waarbij wordt gegarandeerd dat deze een geldige naam is volgens de W3C XML 1.0-specificatie ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft de opgegeven naam, waarbij wordt gegarandeerd dat deze een geldige NmToken is volgens de W3C XML 1.0-specificatie ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Wanneer overschreven in een afgeleide klasse, kopieert alles van de reader naar de writer en verplaatst de reader naar het begin van de volgende sibling. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Kopieert alles van het XPathNavigator-object naar de writer. De positie van de XPathNavigator blijft ongewijzigd. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Wanneer overschreven in een afgeleide klasse, schrijft een processing-instruction met een spatie tussen de naam en de tekst als volgt: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft de namespace-gekwalificeerde naam. Deze methode zoekt de prefix die in scope is voor de gegeven namespace. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Wanneer overschreven in een afgeleide klasse, schrijft ruwe markup handmatig vanuit een tekenbuffer. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft ruwe markup handmatig vanuit een string. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft het begin van een attribuut met de opgegeven lokale naam en namespace-URI. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft het begin van een attribuut met de opgegeven prefix, lokale naam en namespace-URI. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Schrijft het begin van een attribuut met de opgegeven lokale naam. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Wanneer overschreven in een afgeleide klasse, schrijft de XML-declaratie met versie \"1.0\". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Wanneer overschreven in een afgeleide klasse, schrijft de XML-declaratie met versie \"1.0\" en het standalone-attribuut. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft de opgegeven start-tag en koppelt deze aan de opgegeven namespace. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft de opgegeven start-tag en koppelt deze aan de opgegeven namespace en prefix. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft een start-tag met de opgegeven lokale naam. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Wanneer overschreven in een afgeleide klasse, schrijft de opgegeven tekstinhoud. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Wanneer overschreven in een afgeleide klasse, genereert en schrijft de surrogate-character-entity voor het surrogate-tekensparen. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Schrijft de objectwaarde. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Schrijft een [String](../../system/string/)-waarde. |
| virtual void [WriteValue](./writevalue/)(**bool**) | Schrijft een [Boolean](../../system/boolean/)-waarde. |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Schrijft een [DateTime](../../system/datetime/)-waarde. |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Schrijft een [DateTimeOffset](../../system/datetimeoffset/)-waarde. |
| virtual void [WriteValue](./writevalue/)(**double**) | Schrijft een [Double](../../system/double/)-waarde. |
| virtual void [WriteValue](./writevalue/)(**float**) | Schrijft een enkelprecisie-zwevendekommagetal. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Schrijft een [Decimal](../../system/decimal/)-waarde. |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Schrijft een [Int32](../../system/int32/)-waarde. |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Schrijft een [Int64](../../system/int64/)-waarde. |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Wanneer overschreven in een afgeleide klasse, schrijft het opgegeven wit-ruimte-teken. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijstaat alle interne datastructuren. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een shared pointer naar een instantie van deze klasse. |
## Zie ook

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)