---
title: XmlSchema
second_title: Aspose.Slides voor C++ API-referentie
description: Een in-memory representatie van een XML-schema, zoals gespecificeerd in het World Wide Web Consortium (W3C)  en .
type: docs
weight: 79
url: /nl/system.xml.schema/xmlschema/
---
## XmlSchema klasse


Een in-memory representatie van een XML [Schema](../), zoals gespecificeerd in het World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) en [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | Compileert het XML [Schema](../)[Object](../../system/object/) Model (SOM) naar schema-informatie voor validatie. Wordt gebruikt om de syntactische en semantische structuur van de programmatisch gebouwde SOM te controleren. Semantische validatiecontrole wordt uitgevoerd tijdens de compilatie. |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Compileert het XML [Schema](../)[Object](../../system/object/) Model (SOM) naar schema-informatie voor validatie. Wordt gebruikt om de syntactische en semantische structuur van de programmatisch gebouwde SOM te controleren. Semantische validatiecontrole wordt uitgevoerd tijdens de compilatie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetal vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetal vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | Geeft de vorm terug voor attributen gedeclareerd in de doel-namespace van het schema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | Geeft de post-schema-compilatie waarde van alle globale attribuuttgroepen in het schema terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | Geeft de post-schema-compilatie waarde voor alle attributen in het schema terug. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | Geeft het **blockDefault** attribuut terug dat de standaardwaarde van het **block** attribuut instelt op element- en complexetype in de **targetNamespace** van het schema. |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | Geeft de vorm terug voor elementen gedeclareerd in de doel-namespace van het schema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | Geeft de post-schema-compilatie waarde voor alle elementen in het schema terug. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | Geeft het **finalDefault** attribuut terug dat de standaardwaarde van het **final** attribuut instelt op elementen en complexetypen in de doel-namespace van het schema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | Geeft de post-schema-compilatie waarde van alle groepen in het schema terug. |
| [String](../../system/string/) [get_Id](./get_id/)() | Geeft de tekenreeks-ID terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | Geeft de verzameling van ingesloten en geïmporteerde schemas terug. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Geeft aan of het schema is gecompileerd. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | Geeft de verzameling van schema-elementen in het schema terug en wordt gebruikt om nieuwe elementtypen toe te voegen op het **schema** elementniveau. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Geeft het regelnummer in het bestand terug waaraan het **schema** element verwijst. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Geeft de regelpositie in het bestand terug waaraan het **schema** element verwijst. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Geeft de XmlSerializerNamespaces terug die met dit schema-object moeten worden gebruikt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | Geeft de post-schema-compilatie waarde voor alle notaties in het schema terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Geeft de ouder van deze [XmlSchemaObject](../xmlschemaobject/) terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | Geeft de post-schema-compilatie waarde van alle schematypen in het schema terug. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Geeft de bronlocatie voor het bestand dat het schema laadde terug. |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | Geeft de Uniform Resource Identifier (URI) van de doel-namespace van het schema terug. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | Geeft de gekwalificeerde attributen terug die niet tot de doel-namespace van het schema behoren. |
| [String](../../system/string/) [get_Version](./get_version/)() | Geeft de versie van het schema terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die met het object is geassocieerd. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Stelt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Stelt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, alleen het initialiseert een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, alleen initialiseert een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Leest een XML [Schema](../) van de opgegeven [IO::TextReader](../../system.io/textreader/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Leest een XML [Schema](../) van de opgegeven stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Leest een XML [Schema](../) van de opgegeven [XmlReader](../../system.xml/xmlreader/). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Stelt de vorm in voor attributen gedeclareerd in de doel-namespace van het schema. |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Stelt het **blockDefault** attribuut in dat de standaardwaarde van het **block** attribuut op element- en complexetype in de **targetNamespace** van het schema zet. |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Stelt de vorm in voor elementen gedeclareerd in de doel-namespace van het schema. |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Stelt het **finalDefault** attribuut in dat de standaardwaarde van het **final** attribuut op elementen en complexetypen in de doel-namespace van het schema zet. |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | Stelt de tekenreeks-ID in. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Stelt het regelnummer in het bestand in waaraan het **schema** element verwijst. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Stelt de regelpositie in het bestand in waaraan het **schema** element verwijst. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Stelt de XmlSerializerNamespaces in die met dit schema-object moeten worden gebruikt. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Stelt de ouder van deze [XmlSchemaObject](../xmlschemaobject/) in. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Stelt de bronlocatie in voor het bestand dat het schema laadde. |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | Stelt de Uniform Resource Identifier (URI) van de doel-namespace van het schema in. |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Stelt de gekwalificeerde attributen in die niet tot de doel-namespace van het schema behoren. |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | Stelt de versie van het schema in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en geeft de gedeelde referentieteller terug. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Stelt omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Schrijft de XML [Schema](../) naar de opgegeven datastroom. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Schrijft de XML [Schema](../) naar de opgegeven Stream met behulp van de gespecificeerde [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/). |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Schrijft de XML [Schema](../) naar de opgegeven [IO::TextWriter](../../system.io/textwriter/). |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Schrijft de XML [Schema](../) naar de opgegeven TextWriter. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Schrijft de XML [Schema](../) naar de opgegeven [XmlWriter](../../system.xml/xmlwriter/). |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Schrijft de XML [Schema](../) naar de opgegeven [XmlWriter](../../system.xml/xmlwriter/). |
|  [XmlSchema](./xmlschema/)() | Initialiseert een nieuw exemplaar van de [XmlSchema](./) klasse. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialiseert een nieuw exemplaar van de [XmlSchemaObject](../xmlschemaobject/) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | De XML-schema-instance-namespace. Dit veld is constant. |
| static [Namespace](./namespace/) | De XML-schema-namespace. Dit veld is constant. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |

## Opmerkingen



Objecten van deze klasse moeten alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Omwikkel deze klasse altijd met een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om het door te geven aan functies als argument. 

## Zie ook

* Klasse [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)