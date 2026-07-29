---
title: XmlSchema
second_title: Aspose.Slides för C++ API-referens
description: En minnesbaserad representation av ett XML-schema, enligt World Wide Web Consortium (W3C) och .
type: docs
weight: 79
url: /sv/system.xml.schema/xmlschema/
---
## XmlSchema klass


En minnesbaserad representation av en XML [Schema](../), enligt World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) och [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | Kompilerar XML [Schema](../)[Object](../../system/object/) Model (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen av den programatiskt byggda SOM. Semantisk valideringskontroll utförs under kompilering. |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Kompilerar XML [Schema](../)[Object](../../system/object/) Model (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen av den programatiskt byggda SOM. Semantisk valideringskontroll utförs under kompilering. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | Returnerar formen för attribut som deklarerats i schemans mål-namnrymd. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | Returnerar värdet efter schemakompilering för alla globala attributgrupper i schemat. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | Returnerar värdet efter schemakompilering för alla attribut i schemat. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | Returnerar attributet **blockDefault** som sätter standardvärdet för attributet **block** på element och komplexa typer i **targetNamespace** för schemat. |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | Returnerar formen för element som deklarerats i schemans mål-namnrymd. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | Returnerar värdet efter schemakompilering för alla element i schemat. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | Returnerar attributet **finalDefault** som sätter standardvärdet för attributet **final** på element och komplexa typer i schemets mål-namnrymd. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | Returnerar värdet efter schemakompilering för alla grupper i schemat. |
| [String](../../system/string/) [get_Id](./get_id/)() | Returnerar sträng-ID:t. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | Returnerar samlingen av inkluderade och importerade scheman. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Indikerar om schemat har kompilerats. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | Returnerar samlingen av schematelement i schemat och används för att lägga till nya elementtyper på **schema**-elementnivå. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Returnerar radnumret i filen som **schema**-elementet refererar till. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Returnerar radpositionen i filen som **schema**-elementet refererar till. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Returnerar XmlSerializerNamespaces att använda med detta schemaobjekt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | Returnerar värdet efter schemakompilering för alla notationer i schemat. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Returnerar föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | Returnerar värdet efter schemakompilering för alla schematyper i schemat. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Returnerar källplatsen för filen som laddade schemat. |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | Returnerar Uniform Resource Identifier (URI) för schemats mål-namnrymd. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | Returnerar de kvalificerade attributen som inte tillhör schemats mål-namnrymd. |
| [String](../../system/string/) [get_Version](./get_version/)() | Returnerar versionen av schemat. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referencräknardatastruktur associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satset för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Läser en XML [Schema](../) från den tillhandahållna [IO::TextReader](../../system.io/textreader/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Läser en XML [Schema](../) från den tillhandahållna strömmen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Läser en XML [Schema](../) från den tillhandahållna [XmlReader](../../system.xml/xmlreader/). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens för värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Sätter formen för attribut som deklarerats i schemets mål-namnrymd. |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Sätter attributet **blockDefault** som sätter standardvärdet för attributet **block** på element och komplexa typer i **targetNamespace** för schemat. |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Sätter formen för element som deklarerats i schemets mål-namnrymd. |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Sätter attributet **finalDefault** som sätter standardvärdet för attributet **final** på element och komplexa typer i schemets mål-namnrymd. |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | Sätter sträng-ID:t. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Sätter radnumret i filen som **schema**-elementet refererar till. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Sätter radpositionen i filen som **schema**-elementet refererar till. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Sätter XmlSerializerNamespaces att använda med detta schemaobjekt. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Sätter föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Sätter källplatsen för filen som laddade schemat. |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | Sätter Uniform Resource Identifier (URI) för schemats mål-namnrymd. |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Sätter de kvalificerade attributen som inte tillhör schemats mål-namnrymd. |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | Sätter versionen av schemat. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te templateargument till en weak-pekare (istället för shared). Tillåter att byta pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satset för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräkning. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräkning. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Skriver XML [Schema](../) till den tillhandahållna datastreamen. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Skriver XML [Schema](../) till den tillhandahållna Strömmen med den angivna [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/). |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Skriver XML [Schema](../) till den tillhandahållna [IO::TextWriter](../../system.io/textwriter/). |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Skriver XML [Schema](../) till den tillhandahållna TextWriter. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Skriver XML [Schema](../) till den tillhandahållna [XmlWriter](../../system.xml/xmlwriter/). |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Skriver XML [Schema](../) till den tillhandahållna [XmlWriter](../../system.xml/xmlwriter/). |
|  [XmlSchema](./xmlschema/)() | Initierar en ny instans av klassen [XmlSchema](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initierar en ny instans av klassen [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | Destroyar objektet. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | XML-schema-instansens namnrymd. Detta fält är konstant. |
| static [Namespace](./namespace/) | XML-schema namnrymd. Detta fält är konstant. |

## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för delad pekare till en instans av denna klass. |

## Anmärkningar



Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det leder till körfel och/eller assert-fel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument. 

## Se också

* Klass [XmlSchemaObject](../xmlschemaobject/)
* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)