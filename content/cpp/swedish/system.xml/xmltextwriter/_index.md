---
title: XmlTextWriter
second_title: Aspose.Slides för C++ API-referens
description: Representerar en skrivare som tillhandahåller ett snabbt, icke-cachat, endast framåtriktat sätt att generera strömmar eller filer som innehåller XML-data som följer W3C:s Extensible Markup Language (XML) 1.0 och rekommendationerna för Namespaces in XML.
type: docs
weight: 521
url: /sv/system.xml/xmltextwriter/
---
## XmlTextWriter klass


Representerar en skrivare som ger ett snabbt, icke-cachat, endast-framåtriktat sätt att generera strömmar eller filer som innehåller XML-data som följer W3C:s Extensible Markup Language (XML) 1.0 och rekommendationerna för Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Close](./close/)() override | Stänger detta flöde och det underliggande flödet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med det angivna filnamnet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med filnamnet och [XmlWriterSettings](../xmlwritersettings/)-objektet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med det angivna flödet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med flödet och [XmlWriterSettings](../xmlwritersettings/)-objektet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med den angivna TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med TextWriter och [XmlWriterSettings](../xmlwritersettings/)-objekten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med den angivna [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med [Text::StringBuilder](../../system.text/stringbuilder/)- och [XmlWriterSettings](../xmlwritersettings/)-objekten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med det angivna [XmlWriter](../xmlwriter/)-objektet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](../xmlwriter/)-instans med de angivna [XmlWriter](../xmlwriter/)- och [XmlWriterSettings](../xmlwritersettings/)-objekten. |
| void [Dispose](../xmlwriter/dispose/)() override | Frigör alla resurser som används av den aktuella instansen av [XmlWriter](../xmlwriter/)-klassen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| void [Flush](./flush/)() override | Spolar ut allt som finns i bufferten till de underliggande strömmarna och spolar även den underliggande strömmen. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Returnerar det underliggande strömobjektet. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Anger hur utdata formateras. |
| **int32_t** [get_Indentation](./get_indentation/)() | Returnerar hur många IndentChars som ska skrivas för varje nivå i hierarkin när [XmlTextWriter::set_Formatting](./set_formatting/) är satt till [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Returnerar vilket tecken som ska användas för indragning när [XmlTextWriter::set_Formatting](./set_formatting/) är satt till [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Returnerar ett värde som indikerar om namnrymdsstöd ska användas. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Returnerar vilket tecken som ska användas för att citera attributvärden. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Returnerar [XmlWriterSettings](../xmlwritersettings/)-objektet som användes för att skapa denna [XmlWriter](../xmlwriter/)-instans. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Returnerar skrivarnas tillstånd. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Returnerar det aktuella **xml:lang**-omfånget. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Returnerar ett XmlSpace som representerar det aktuella **xml:space**-omfånget. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Returnerar det närmaste prefixet som definierats i det aktuella namnrymdsomfånget för namnrymdens URI. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med det angivna värdet. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Anger hur utdata formateras. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Ställer in hur många IndentChars som ska skrivas för varje nivå i hierarkin när [XmlTextWriter::set_Formatting](./set_formatting/) är satt till [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Ställer in vilket tecken som ska användas för indragning när [XmlTextWriter::set_Formatting](./set_formatting/) är satt till [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ställer in ett värde som indikerar om namnrymdsstöd ska användas. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Ställer in vilket tecken som ska användas för att citera attributvärden. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | När den överskrivs i en avledd klass, skriver ut alla attribut som finns på den aktuella platsen i [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den överskrivs i en avledd klass, skriver ett attribut med angivet lokalt namn, namnrymds-URI och värde. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den överskrivs i en avledd klass, skriver ut attributet med angivet lokalt namn och värde. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den överskrivs i en avledd klass, skriver ut attributet med angivet prefix, lokalt namn, namnrymds-URI och värde. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Kodar de angivna binära bytena som base64 och skriver ut den resulterande texten. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Kodar de angivna binära bytena som binhex och skriver ut den resulterande texten. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Skriver ut ett **...**-block som innehåller den angivna texten. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Tvingar generering av en teckenenhet för det angivna Unicode-teckenvärdet. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Skriver text en buffert åt gången. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Skriver ut en kommentar **** som innehåller den angivna texten. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Skriver DOCTYPE-deklarationen med det angivna namnet och valfria attribut. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver ett element med angivet lokalt namn och värde. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver ett element med angivet lokalt namn, namnrymds-URI och värde. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver ett element med angivet prefix, lokalt namn, namnrymds-URI och värde. |
| void [WriteEndAttribute](./writeendattribute/)() override | Stänger det föregående [XmlTextWriter::WriteStartAttribute](./writestartattribute/)-anropet. |
| void [WriteEndDocument](./writeenddocument/)() override | Stänger alla öppna element eller attribut och sätter skrivaren tillbaka till Start-tillståndet. |
| void [WriteEndElement](./writeendelement/)() override | Stänger ett element och poppar den motsvarande namnrymdsomfånget. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Skriver ut en entitetsreferens som **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Stänger ett element och poppar den motsvarande namnrymdsomfånget. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Skriver ut det angivna namnet och säkerställer att det är ett giltigt namn enligt [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Skriver ut det angivna namnet och säkerställer att det är en giltig **NmToken** enligt [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | När den överskrivs i en avledd klass, kopierar allt från läsaren till skrivaren och flyttar läsaren till början av nästa syskon. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Kopierar allt från XPathNavigator-objektet till skrivaren. XPathNavigator-positionen förblir oförändrad. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Skriver ut en processinstruktion med ett mellanslag mellan namn och text enligt: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Skriver ut det namnrymdskvalificerade namnet. Denna metod slår upp prefixet som är i omfång för den angivna namnrymden. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Skriver rå markup manuellt från en teckenbuffer. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Skriver rå markup manuellt från en sträng. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Skriver början av ett attribut. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver början av ett attribut med angivet lokalt namn och namnrymds-URI. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Skriver början av ett attribut med angivet lokalt namn. |
| void [WriteStartDocument](./writestartdocument/)() override | Skriver XML-deklarationen med versionen "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Skriver XML-deklarationen med versionen "1.0" och attributet standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Skriver den angivna starttaggen och associerar den med den givna namnrymden och prefixet. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den överskrivs i en avledd klass, skriver den angivna starttaggen och associerar den med den givna namnrymden. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | När den överskrivs i en avledd klass, skriver ut en starttagg med det angivna lokala namnet. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Skriver den givna textinnehållet. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Genererar och skriver teckenenheten för surrogatparens två tecken. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Skriver objektvärdet. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Skriver ett [String](../../system/string/)-värde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Skriver ett [Boolean](../../system/boolean/)-värde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Skriver ett [DateTime](../../system/datetime/)-värde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Skriver ett [DateTimeOffset](../../system/datetimeoffset/)-värde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Skriver ett [Double](../../system/double/)-värde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Skriver ett flyttal med enkel precision. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Skriver ett [Decimal](../../system/decimal/)-värde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Skriver ett [Int32](../../system/int32/)-värde. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Skriver ett [Int64](../../system/int64/)-värde. |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Skriver ut det givna blanksteget. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Skapar en instans av [XmlTextWriter](./)-klassen med den angivna strömmen och kodningen. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Skapar en instans av [XmlTextWriter](./)-klassen med den angivna filen. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Skapar en instans av [XmlTextWriter](./)-klassen med den angivna TextWriter. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för smartpekare till en instans av denna klass. |
## Anmärkningar



Det rekommenderas att använda [XmlWriter](../xmlwriter/)-klassen istället. 

Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig instanser av denna typ på stacken eller med operatorn new, då det leder till körfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. 

## Se också

* Klass [XmlWriter](../xmlwriter/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)