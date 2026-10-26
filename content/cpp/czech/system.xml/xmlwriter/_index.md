---
title: XmlWriter
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Reprezentuje zapisovač, který poskytuje rychlý, nebuforovaný a pouze dopředný způsob generování proudů nebo souborů obsahujících XML data.
type: docs
weight: 573
url: /cs/system.xml/xmlwriter/
---
## XmlWriter třída

Reprezentuje zapisovač, který poskytuje rychlý, nebuforovaný a pouze dopředný způsob generování proudů nebo souborů obsahujících XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [Close](./close/)() | Když je v odvozené třídě přepsena, uzavře tento proud a podkladový proud. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlWriter](./) pomocí zadaného názvu souboru. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](./) pomocí názvu souboru a objektu [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Vytvoří novou instanci [XmlWriter](./) pomocí zadaného proudu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](./) pomocí proudu a objektu [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Vytvoří novou instanci [XmlWriter](./) pomocí zadaného TextWriteru. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](./) pomocí TextWriteru a objektů [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Vytvoří novou instanci [XmlWriter](./) pomocí zadaného [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](./) pomocí objektů [Text::StringBuilder](../../system.text/stringbuilder/) a [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Vytvoří novou instanci [XmlWriter](./) pomocí zadaného objektu [XmlWriter](./). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Vytvoří novou instanci [XmlWriter](./) pomocí zadaných objektů [XmlWriter](./) a [XmlWriterSettings](../xmlwritersettings/). |
| void [Dispose](./dispose/)() override | Uvolní všechny zdroje používané aktuální instancí třídy [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty podle reference. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual void [Flush](./flush/)() | Když je v odvozené třídě přepsena, vyprázdní vše, co je v bufferu, do podkladových proudů a také vyprázdní podkladový proud. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Vrací objekt [XmlWriterSettings](../xmlwritersettings/) použitý k vytvoření této instance [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Když je v odvozené třídě přepsena, získá stav zapisovače. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Když je v odvozené třídě přepsena, získá aktuální rozsah **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Když je v odvozené třídě přepsena, získá XmlSpace představující aktuální rozsah **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt hlídače [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Když je v odvozené třídě přepsena, vrací nejbližší předponu definovanou v aktuálním rozsahu jmenného prostoru pro URI jmenného prostoru. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených odkazů o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt hlídače [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Když je v odvozené třídě přepsena, zapíše všechny atributy nalezené na aktuální pozici v [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše atribut se zadaným místním názvem, URI jmenného prostoru a hodnotou. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše atribut se zadaným místním názvem a hodnotou. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše atribut se zadanou předponou, místním názvem, URI jmenného prostoru a hodnotou. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Když je v odvozené třídě přepsena, zakóduje zadané binární bajty jako Base64 a zapíše vzniklý text. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Když je v odvozené třídě přepsena, zakóduje zadané binární bajty jako **BinHex** a zapíše vzniklý text. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Když je v odvozené třídě přepsena, zapíše blok **...** obsahující zadaný text. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Když je v odvozené třídě přepsena, vynutí generování znakové entity pro zadanou hodnotu Unicode znaku. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Když je v odvozené třídě přepsena, zapisuje text po jedné vyrovnávací paměti. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Když je v odvozené třídě přepsena, zapíše komentář **** obsahující zadaný text. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše deklaraci DOCTYPE se zadaným názvem a volitelnými atributy. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše prvek se zadaným místním názvem a hodnotou. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše prvek se zadaným místním názvem, URI jmenného prostoru a hodnotou. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše prvek se zadanou předponou, místním názvem, URI jmenného prostoru a hodnotou. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Když je v odvozené třídě přepsena, uzavře předchozí volání XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | Když je v odvozené třídě přepsena, uzavře všechny otevřené elementy nebo atributy a vrátí zapisovač do stavu Start. |
| virtual void [WriteEndElement](./writeendelement/)() | Když je v odvozené třídě přepsena, uzavře jeden element a odstraní odpovídající rozsah jmenného prostoru. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše odkaz na entitu jako **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Když je v odvozené třídě přepsena, uzavře jeden element a odstraní odpovídající rozsah jmenného prostoru. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše zadaný název a zajistí, že je platný podle doporučení W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše zadaný název a zajistí, že je platný NmToken podle doporučení W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Když je v odvozené třídě přepsena, zkopíruje vše z čtečky do zapisovače a posune čtečku na začátek dalšího sourozence. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Zkopíruje vše z objektu XPathNavigator do zapisovače. Pozice XPathNavigator zůstává beze změny. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Když je v odvozené třídě přepsena, zapíše instrukci zpracování s mezerou mezi názvem a textem následujícím způsobem: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše jmenně kvalifikovaný název. Tato metoda vyhledá předponu, která je v rozsahu pro daný prostor jmen. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Když je v odvozené třídě přepsena, zapisuje surový markup ručně z vyrovnávacího bufferu znaků. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapisuje surový markup ručně z řetězce. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše začátek atributu se zadaným místním názvem a URI jmenného prostoru. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše začátek atributu se zadanou předponou, místním názvem a URI jmenného prostoru. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Zapíše začátek atributu se zadaným místním názvem. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Když je v odvozené třídě přepsena, zapíše deklaraci XML s verzí "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Když je v odvozené třídě přepsena, zapíše deklaraci XML s verzí "1.0" a atributem standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše zadaný úvodní tag a přiřadí jej k danému jmennému prostoru. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše zadaný úvodní tag a přiřadí jej k danému jmennému prostoru a předponě. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše úvodní tag se zadaným místním názvem. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Když je v odvozené třídě přepsena, zapíše zadaný textový obsah. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Když je v odvozené třídě přepsena, vygeneruje a zapíše entitu náhradního znaku pro dvojici náhradních znaků. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Zapíše hodnotu objektu. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Zapíše hodnotu [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Zapíše hodnotu [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Zapíše hodnotu [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Zapíše hodnotu [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Zapíše hodnotu [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Zapíše číslo s jednoduchou přesností. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Zapíše hodnotu [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Zapíše hodnotu [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Zapíše hodnotu [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Když je v odvozené třídě přepsena, zapíše zadané bílé znaky. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |
## Viz také

* Třída [IDisposable](../../system/idisposable/)
* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)