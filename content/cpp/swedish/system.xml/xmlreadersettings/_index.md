---
title: XmlReaderSettings
second_title: Aspose.Slides för C++ API-referens
description: "Anger en uppsättning funktioner som ska stödjas på XmlReader-objektet som skapas av XmlReader::Create-metoden."
type: docs
weight: 443
url: /sv/system.xml/xmlreadersettings/
---
## XmlReaderSettings klass


Specifies a set of features to support on the [XmlReader](../xmlreader/) object created by the [XmlReader::Create](../xmlreader/create/) method.

```cpp
class XmlReaderSettings : public System::Object
```

## Metoder

| Method | Description |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Skapar en kopia av [XmlReaderSettings](./)-instansen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Returnerar ett värde som anger om teckenkontroll ska utföras. |
| **bool** [get_CloseInput](./get_closeinput/)() | Returnerar ett värde som anger om den underliggande strömmen eller TextReader ska stängas när läsaren stängs. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Returnerar den efterlevnadsnivå som [XmlReader](../xmlreader/) kommer att följa. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Returnerar ett värde som bestämmer bearbetning av DTD-er. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Returnerar ett värde som anger om kommentarer ska ignoreras. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Returnerar ett värde som anger om processinstruktioner ska ignoreras. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Returnerar ett värde som anger om insignifikant blanksteg ska ignoreras. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Returnerar radnumrets offset för [XmlReader](../xmlreader/)-objektet. |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Returnerar radpositionens offset för [XmlReader](../xmlreader/)-objektet. |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Returnerar ett värde som anger det maximalt tillåtna antalet tecken i ett dokument som resultat av att entiteter expanderas. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Returnerar ett värde som anger det maximalt tillåtna antalet tecken i ett XML-dokument. Ett nollvärde (0) betyder att det inte finns några begränsningar för dokumentets storlek. Ett icke-nollvärde specificerar den maximala storleken i tecken. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Returnerar [XmlNameTable](../xmlnametable/) som används för atomiserade strängjämförelser. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Returnerar ett värde som anger om bearbetning av dokumenttypdefinition (DTD) ska förbjudas. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Returnerar XmlSchemaSet som ska användas vid schemavalidering. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Returnerar ett värde som anger schemavalideringsinställningarna. Denna inställning gäller [XmlReader](../xmlreader/)-objekt som validerar scheman ([XmlReaderSettings::get_ValidationType](./get_validationtype/)-värdet är [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Returnerar ett värde som anger om [XmlReader](../xmlreader/) ska utföra validering eller typtilldelning vid läsning. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräkningsdatastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satsen. Anropas direkt eller via [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar den delade referensräkningen med angivet värde. |
| void [Reset](./reset/)() | Återställer medlemmarna i inställningsklassen till deras standardvärden. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Sätter ett värde som anger om teckenkontroll ska utföras. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Sätter ett värde som anger om den underliggande strömmen eller TextReader ska stängas när läsaren stängs. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Sätter den efterlevnadsnivå som [XmlReader](../xmlreader/) ska följa. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Sätter ett värde som bestämmer bearbetning av DTD-er. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Sätter ett värde som anger om kommentarer ska ignoreras. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Sätter ett värde som anger om processinstruktioner ska ignoreras. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Sätter ett värde som anger om insignifikant blanksteg ska ignoreras. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Sätter radnumrets offset för [XmlReader](../xmlreader/)-objektet. |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Sätter radpositionens offset för [XmlReader](../xmlreader/)-objektet. |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Sätter ett värde som anger det maximalt tillåtna antalet tecken i ett dokument som resultat av att entiteter expanderas. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Sätter ett värde som anger det maximalt tillåtna antalet tecken i ett XML-dokument. Ett nollvärde (0) betyder att det inte finns några begränsningar för dokumentets storlek. Ett icke-nollvärde specificerar den maximala storleken i tecken. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Sätter [XmlNameTable](../xmlnametable/) som används för atomiserade strängjämförelser. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Sätter ett värde som anger om bearbetning av dokumenttypdefinition (DTD) ska förbjudas. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Sätter XmlSchemaSet som ska användas vid schemavalidering. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Sätter ett värde som anger schemavalideringsinställningarna. Denna inställning gäller [XmlReader](../xmlreader/)-objekt som validerar scheman ([XmlReaderSettings::get_ValidationType](./get_validationtype/)-värdet är [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Sätter ett värde som anger om [XmlReader](../xmlreader/) ska utföra validering eller typtilldelning vid läsning. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Sätter [XmlResolver](../xmlresolver/) som används för att komma åt externa dokument. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar det aktuella värdet av den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräkningen. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräkningen. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsningupphävning enligt C# lock()-satsen. Anropas direkt eller via [LockContext](../../system/lockcontext/)-vaktobjekt. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Lägger till en händelsehanterare som triggas när läsaren stöter på valideringsfel. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Tar bort en händelsehanterare som triggas när läsaren stöter på valideringsfel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräkningen. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräkningen. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Initierar en ny instans av [XmlReaderSettings](./)-klassen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Description |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Anmärkningar

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument. 

## Se också

* Klass [Object](../../system/object/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)