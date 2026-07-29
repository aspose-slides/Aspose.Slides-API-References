---
title: XmlWriter
second_title: Aspose.Slides för C++ API-referens
description: Representerar en skribent som tillhandahåller ett snabbt, icke-cachelagrat, framåtriktat sätt att generera strömmar eller filer som innehåller XML-data.
type: docs
weight: 573
url: /sv/system.xml/xmlwriter/
---
## XmlWriter klass

Representerar en skribent som tillhandahåller ett snabbt, icke-cachelagrat, framåtriktat sätt att generera strömmar eller filer som innehåller XML-data.

```cpp
class XmlWriter : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Close](./close/)() | När den åsidosätts i en härledd klass, stänger den här strömmen och den underliggande strömmen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Skapar en ny [XmlWriter](./)-instans med det angivna filnamnet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](./)-instans med filnamnet och [XmlWriterSettings](../xmlwritersettings/)-objektet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Skapar en ny [XmlWriter](./)-instans med den angivna strömmen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](./)-instans med strömmen och [XmlWriterSettings](../xmlwritersettings/)-objektet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Skapar en ny [XmlWriter](./)-instans med den angivna TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](./)-instans med TextWriter och [XmlWriterSettings](../xmlwritersettings/)-objekt. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Skapar en ny [XmlWriter](./)-instans med den angivna [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](./)-instans med [Text::StringBuilder](../../system.text/stringbuilder/)- och [XmlWriterSettings](../xmlwritersettings/)-objekten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Skapar en ny [XmlWriter](./)-instans med det angivna [XmlWriter](./)-objektet. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Skapar en ny [XmlWriter](./)-instans med de angivna [XmlWriter](./)- och [XmlWriterSettings](../xmlwritersettings/)-objekten. |
| void [Dispose](./dispose/)() override | Frigör alla resurser som används av den aktuella instansen av [XmlWriter](./)-klassen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika, även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika, även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual void [Flush](./flush/)() | När den åsidosätts i en härledd klass, tömmer den allt som finns i bufferten till de underliggande strömmarna och tömmer även den underliggande strömmen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Returnerar [XmlWriterSettings](../xmlwritersettings/)-objektet som användes för att skapa denna [XmlWriter](./)-instans. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | När den åsidosätts i en härledd klass, hämtar den skrivarens tillstånd. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | När den åsidosätts i en härledd klass, hämtar den aktuellt **xml:lang**-omfång. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | När den åsidosätts i en härledd klass, hämtar den ett XmlSpace-objekt som representerar det aktuella **xml:space**-omfånget. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar räknar-för-referenser-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropas direkt eller med [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | När den åsidosätts i en härledd klass, returnerar den det närmaste prefixet som definierats i det aktuella namnrymdsomfånget för namnrymd-URI:n. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-sats. Anropas direkt eller med [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | När den åsidosätts i en härledd klass, skriver den ut alla attribut som finns på den aktuella positionen i [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver den ett attribut med det angivna lokala namnet, namnrymd-URI och värde. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver den ut attributet med det angivna lokala namnet och värdet. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver den ut attributet med det angivna prefixet, lokala namnet, namnrymd-URI och värde. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | När den åsidosätts i en härledd klass, kodar de angivna binära bytes som Base64 och skriver ut den resulterande texten. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | När den åsidosätts i en härledd klass, kodar de angivna binära bytes som **BinHex** och skriver ut den resulterande texten. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | När den åsidosätts i en härledd klass, skriver den ut ett **...**-block som innehåller den angivna texten. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | När den åsidosätts i en härledd klass, tvingar den generering av en teckenenhet för det angivna Unicode-teckenvärdet. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | När den åsidosätts i en härledd klass, skriver den text en buffer åt gången. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | När den åsidosätts i en härledd klass, skriver den ut en kommentar **** som innehåller den angivna texten. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver den DOCTYPE-deklarationen med det angivna namnet och valfria attribut. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver ett element med det angivna lokala namnet och värdet. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver ett element med det angivna lokala namnet, namnrymd-URI och värde. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver ett element med det angivna prefixet, lokala namnet, namnrymd-URI och värde. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | När den åsidosätts i en härledd klass, avslutar den föregående XmlWriter::WriteStartAttribute(String,String)-anropet. |
| virtual void [WriteEndDocument](./writeenddocument/)() | När den åsidosätts i en härledd klass, stänger alla öppna element eller attribut och återställer skrivarens Start-tillstånd. |
| virtual void [WriteEndElement](./writeendelement/)() | När den åsidosätts i en härledd klass, stänger ett element och poppar motsvarande namnrymdsomfång. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver ut en enhetsreferens som **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | När den åsidosätts i en härledd klass, stänger ett element och poppar motsvarande namnrymdsomfång. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver ut det angivna namnet och säkerställer att det är ett giltigt namn enligt W3C XML 1.0-rekommendationen ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver ut det angivna namnet och säkerställer att det är en giltig NmToken enligt W3C XML 1.0-rekommendationen ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | När den åsidosätts i en härledd klass, kopierar den allt från läsaren till skribenten och flyttar läsaren till början av nästa syskon. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Kopierar allt från XPathNavigator-objektet till skribenten. XPathNavigator-positionen förblir oförändrad. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | När den åsidosätts i en härledd klass, skriver den ut en processinstruktion med ett mellanslag mellan namn och text på följande sätt: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver den ut det namnrymd-kvalificerade namnet. Metoden letar upp prefixet som är i scope för den angivna namnrymden. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | När den åsidosätts i en härledd klass, skriver rå markup manuellt från en teckenbuffer. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver rå markup manuellt från en sträng. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver början av ett attribut med det angivna lokala namnet och namnrymd-URI. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver början av ett attribut med det angivna prefixet, lokala namnet och namnrymd-URI. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Skriver början av ett attribut med det angivna lokala namnet. |
| virtual void [WriteStartDocument](./writestartdocument/)() | När den åsidosätts i en härledd klass, skriver XML-deklarationen med version "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | När den åsidosätts i en härledd klass, skriver XML-deklarationen med version "1.0" och attributet standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver den angivna starttaggen och kopplar den till den givna namnrymden. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver den den angivna starttaggen och kopplar den till den givna namnrymden och prefixet. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver en starttagg med det angivna lokala namnet. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | När den åsidosätts i en härledd klass, skriver den den angivna textinnehållet. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | När den åsidosätts i en härledd klass, genererar och skriver surrogate-teckenenheten för surrogate-teckenparet. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Skriver objektvärdet. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Skriver ett [String](../../system/string/)-värde. |
| virtual void [WriteValue](./writevalue/)(**bool**) | Skriver ett [Boolean](../../system/boolean/)-värde. |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Skriver ett [DateTime](../../system/datetime/)-värde. |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Skriver ett [DateTimeOffset](../../system/datetimeoffset/)-värde. |
| virtual void [WriteValue](./writevalue/)(**double**) | Skriver ett [Double](../../system/double/)-värde. |
| virtual void [WriteValue](./writevalue/)(**float**) | Skriver ett flyttal med enkelprecision. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Skriver ett [Decimal](../../system/decimal/)-värde. |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Skriver ett [Int32](../../system/int32/)-värde. |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Skriver ett [Int64](../../system/int64/)-värde. |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | När den åsidosätts i en härledd klass, skriver den ut det givna blanksteget. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Se även

* Klass [IDisposable](../../system/idisposable/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)