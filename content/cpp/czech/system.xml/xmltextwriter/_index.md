---
title: XmlTextWriter
second_title: Referenční příručka API pro Aspose.Slides pro C++
description: Representuje zapisovač, který poskytuje rychlý, neukládaný do bufferu, pouze dopředný způsob generování proudů nebo souborů obsahujících data XML, která vyhovují doporučením W3C Extensible Markup Language (XML) 1.0 a Namespaces in XML.
type: docs
weight: 521
url: /cs/system.xml/xmltextwriter/
---
## XmlTextWriter třída

Representuje zapisovač, který poskytuje rychlý, neukládaný do vyrovnávací paměti, pouze dopředný způsob generování proudů nebo souborů obsahujících data XML, která vyhovují doporučením W3C Extensible Markup Language (XML) 1.0 a Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Close](./close/)() override | Uzavře tento proud a podkladový proud. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí zadaného názvu souboru. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí názvu souboru a objektu [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí zadaného proudu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí proudu a objektu [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí zadaného TextWriteru. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí TextWriteru a objektů [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí zadaného [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí objektů [Text::StringBuilder](../../system.text/stringbuilder/) a [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí zadaného objektu [XmlWriter](../xmlwriter/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](../xmlwriter/) pomocí zadaných objektů [XmlWriter](../xmlwriter/) a [XmlWriterSettings](../xmlwritersettings/). |
| void [Dispose](../xmlwriter/dispose/)() override | Uvolní všechny prostředky používané aktuální instancí třídy [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| void [Flush](./flush/)() override | Vyprázdní vše, co je v bufferu, do podkladových proudů a také vyprázdní podkladový proud. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Vrací objekt podkladového proudu. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Udává, jak je výstup formátován. |
| **int32_t** [get_Indentation](./get_indentation/)() | Vrací, kolik znaků odsazení (IndentChars) se zapíše pro každou úroveň v hierarchii, když je [XmlTextWriter::set_Formatting](./set_formatting/) nastaveno na [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Vrací, který znak se použije pro odsazení, když je [XmlTextWriter::set_Formatting](./set_formatting/) nastaveno na [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Vrací hodnotu indikující, zda se má podporovat jmenný prostor. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Vrací, který znak se použije k uvozování hodnot atributů. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Vrací objekt [XmlWriterSettings](../xmlwritersettings/) použitého k vytvoření této instance [XmlWriter](../xmlwriter/). |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Vrací stav zapisovače. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Vrací aktuální rozsah **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Vrací XmlSpace představující aktuální rozsah **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Vrací nejbližší prefix definovaný v aktuálním rozsahu jmenného prostoru pro URI jmenného prostoru. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Udává, jak je výstup formátován. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Nastavuje, kolik znaků odsazení (IndentChars) se zapíše pro každou úroveň v hierarchii, když je [XmlTextWriter::set_Formatting](./set_formatting/) nastaveno na [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Nastavuje, který znak se použije pro odsazení, když je [XmlTextWriter::set_Formatting](./set_formatting/) nastaveno na [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Nastavuje hodnotu indikující, zda se má podporovat jmenný prostor. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Nastavuje, který znak se použije k uvozování hodnot atributů. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do režimu slabého ukazatele. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje konverzi vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Při přepsání v odvozené třídě zapíše všechny atributy nalezené na aktuální pozici v [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Při přepsání v odvozené třídě zapíše atribut se zadaným lokálním názvem, URI jmenného prostoru a hodnotou. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Při přepsání v odvozené třídě zapíše atribut se zadaným lokálním názvem a hodnotou. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Při přepsání v odvozené třídě zapíše atribut se zadaným prefixem, lokálním názvem, URI jmenného prostoru a hodnotou. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Zakóduje zadané binární bajty do base64 a zapíše vzniklý text. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Zakóduje zadané binární bajty do binhex a zapíše vzniklý text. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Zapíše blok **...** obsahující zadaný text. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Vynutí generování znakové entity pro zadanou hodnotu Unicode znaku. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Zapíše text po jedné vyrovnávací paměti. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Zapíše komentář **** obsahující zadaný text. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Zapíše deklaraci DOCTYPE se zadaným názvem a volitelnými atributy. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše element se zadaným lokálním názvem a hodnotou. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše element se zadaným lokálním názvem, URI jmenného prostoru a hodnotou. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše element se zadaným prefixem, lokálním názvem, URI jmenného prostoru a hodnotou. |
| void [WriteEndAttribute](./writeendattribute/)() override | Uzavře předchozí volání [XmlTextWriter::WriteStartAttribute](./writestartattribute/). |
| void [WriteEndDocument](./writeenddocument/)() override | Uzavře všechny otevřené elementy nebo atributy a vrátí zapisovač do stavu Start. |
| void [WriteEndElement](./writeendelement/)() override | Uzavře jeden element a odstraní odpovídající rozsah jmenného prostoru. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Zapíše odkaz na entitu jako **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Uzavře jeden element a odstraní odpovídající rozsah jmenného prostoru. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Zapíše zadaný název, přičemž zajišťuje, že je platný podle [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Zapíše zadaný název, přičemž zajišťuje, že je platný **NmToken** podle [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Při přepsání v odvozené třídě zkopíruje vše z čtečky do zapisovače a přesune čtečku na začátek následujícího sourozence. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Zkopíruje vše z objektu XPathNavigator do zapisovače. Pozice XPathNavigatoru zůstává beze změny. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Zapíše instrukci zpracování s mezerou mezi názvem a textem takto: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Zapíše jmenně kvalifikovaný název. Tato metoda vyhledá prefix, který je v rozsahu pro daný jmenný prostor. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Zapíše surové značky ručně z vyrovnávací paměti znaků. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Zapíše surové značky ručně ze řetězce. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Zapíše začátek atributu. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše začátek atributu se zadaným lokálním názvem a URI jmenného prostoru. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Zapíše začátek atributu se zadaným lokálním názvem. |
| void [WriteStartDocument](./writestartdocument/)() override | Zapíše deklaraci XML s verzí "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Zapíše deklaraci XML s verzí "1.0" a atributem standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Zapíše zadaný úvodní tag a přiřadí jej k danému jmennému prostoru a prefixu. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Při přepsání v odvozené třídě zapíše zadaný úvodní tag a přiřadí jej k danému jmennému prostoru. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Při přepsání v odvozené třídě zapíše úvodní tag se zadaným lokálním názvem. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Zapíše daný textový obsah. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Vygeneruje a zapíše znakovou entitu pro pár surrogate znaků. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Zapíše hodnotu objektu. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Zapíše hodnotu [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Zapíše hodnotu [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Zapíše hodnotu [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Zapíše hodnotu [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Zapíše hodnotu [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Zapíše číslo s jednoduchou přesností (float). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Zapíše hodnotu [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Zapíše hodnotu [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Zapíše hodnotu [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Zapíše zadanou bílou mezeru. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Vytvoří instanci třídy [XmlTextWriter](./) pomocí zadaného proudu a kódování. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Vytvoří instanci třídy [XmlTextWriter](./) pomocí zadaného souboru. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Vytvoří instanci třídy [XmlTextWriter](./) pomocí zadaného TextWriteru. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Definice typů

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |

## Poznámky

Je doporučeno místo toho použít třídu [XmlWriter](../xmlwriter/).

Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku nebo pomocí operator new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a používejte tento ukazatel k předávání jako argument funkcím.

## Viz také

* Třída [XmlWriter](../xmlwriter/)
* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)