---
title: XmlWriterSettings
second_title: Aspose.Slides för C++ API-referens
description: "Anger en uppsättning funktioner som ska stödjas på XmlWriter-objektet som skapats av XmlWriter::Create-metoden."
type: docs
weight: 586
url: /sv/system.xml/xmlwritersettings/
---
## XmlWriterSettings klass

Specificerar en uppsättning funktioner som ska stödjas på [XmlWriter](../xmlwriter/)-objektet som skapats av [XmlWriter::Create](../xmlwriter/create/)-metoden.

```cpp
class XmlWriterSettings : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Skapar en kopia av [XmlWriterSettings](./)-instansen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Returnerar ett värde som indikerar om XML-skrivaren ska kontrollera att alla tecken i dokumentet följer avsnittet "2.2 Characters" i W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Returnerar ett värde som indikerar om [XmlWriter](../xmlwriter/) också ska stänga den underliggande strömmen eller TextWriter när [XmlWriter::Close](../xmlwriter/close/)-metoden anropas. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Returnerar den konformitetsnivå som XML-skrivaren kontrollerar XML-utdata för. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Returnerar ett värde som indikerar om [XmlWriter](../xmlwriter/) inte kodar URI-attribut. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Returnerar vilken typ av textkodning som ska användas. |
| **bool** [get_Indent](./get_indent/)() | Returnerar ett värde som indikerar om element ska indenteras. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Returnerar teckensträngen som ska användas vid indentering. Denna inställning används när [XmlWriterSettings::set_Indent](./set_indent/)-värdet är **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Returnerar ett värde som indikerar om [XmlWriter](../xmlwriter/) ska ta bort duplicerade namnrymdsdeklarationer vid generering av XML-innehåll. Standardbeteendet är att skrivaren skriver ut alla namnrymdsdeklarationer som finns i skrivarens namnrymdslösare. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Returnerar teckensträngen som ska användas för radbrytningar. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Returnerar ett värde som indikerar om radbrytningar i utdata ska normaliseras. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Returnerar ett värde som indikerar om attribut ska skrivas på en ny rad. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Returnerar ett värde som indikerar om en XML-deklaration ska utelämnas. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Returnerar metoden som används för att serialisera [XmlWriter](../xmlwriter/)-utdata. |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Returnerar ett värde som indikerar om [XmlWriter](../xmlwriter/) kommer att lägga till avslutande taggar för alla oavslutade elementtaggar när [XmlWriter::Close](../xmlwriter/close/)-metoden anropas. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropas direkt eller via [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens för värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [Reset](./reset/)() | Återställer medlemmarna i inställningsklassen till deras standardvärden. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Ställer in ett värde som indikerar om XML-skrivaren ska kontrollera att alla tecken i dokumentet följer avsnittet "2.2 Characters" i W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Ställer in ett värde som indikerar om [XmlWriter](../xmlwriter/) också ska stänga den underliggande strömmen eller TextWriter när [XmlWriter::Close](../xmlwriter/close/)-metoden anropas. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Ställer in den konformitetsnivå som XML-skrivaren kontrollerar XML-utdata för. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Ställer in ett värde som indikerar om [XmlWriter](../xmlwriter/) inte kodar URI-attribut. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Ställer in vilken typ av textkodning som ska användas. |
| void [set_Indent](./set_indent/)(**bool**) | Ställer in ett värde som indikerar om element ska indenteras. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Ställer in teckensträngen som ska användas vid indentering. Denna inställning används när [XmlWriterSettings::set_Indent](./set_indent/)-värdet är **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Ställer in ett värde som indikerar om [XmlWriter](../xmlwriter/) ska ta bort duplicerade namnrymdsdeklarationer vid generering av XML-innehåll. Standardbeteendet är att skrivaren skriver ut alla namnrymdsdeklarationer som finns i skrivarens namnrymdslösare. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Ställer in teckensträngen som ska användas för radbrytningar. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Ställer in ett värde som indikerar om radbrytningar i utdata ska normaliseras. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Ställer in ett värde som indikerar om attribut ska skrivas på en ny rad. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Ställer in ett värde som indikerar om en XML-deklaration ska utelämnas. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Ställer in ett värde som indikerar om [XmlWriter](../xmlwriter/) kommer att lägga till avslutande taggar för alla oavslutade elementtaggar när [XmlWriter::Close](../xmlwriter/close/)-metoden anropas. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropas direkt eller via [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Initierar en ny instans av [XmlWriterSettings](./)-klassen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Typedefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Anmärkningar

Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körningstidfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. 

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)