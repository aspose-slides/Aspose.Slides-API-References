---
title: XmlReaderSettings
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert een reeks kenmerken die ondersteund moeten worden op het XmlReader-object dat is gecreëerd door de XmlReader::Create-methode."
type: docs
weight: 443
url: /nl/system.xml/xmlreadersettings/
---
## XmlReaderSettings klasse


Specificeert een set kenmerken die ondersteund moeten worden op het [XmlReader](../xmlreader/) object dat is gecreëerd door de [XmlReader::Create](../xmlreader/create/) methode.

```cpp
class XmlReaderSettings : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Maakt een kopie van de [XmlReaderSettings](./) instantie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-punt vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-punt vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Retourneert een waarde die aangeeft of karaktercontrole moet worden uitgevoerd. |
| **bool** [get_CloseInput](./get_closeinput/)() | Retourneert een waarde die aangeeft of de onderliggende stream of TextReader moet worden gesloten wanneer de lezer wordt gesloten. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Retourneert het conformiteitsniveau waaraan de [XmlReader](../xmlreader/) zal voldoen. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Retourneert een waarde die de verwerking van DTD's bepaalt. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Retourneert een waarde die aangeeft of commentaren genegeerd moeten worden. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Retourneert een waarde die aangeeft of verwerkingsinstructies genegeerd moeten worden. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Retourneert een waarde die aangeeft of onbeduidende witruimte genegeerd moet worden. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Retourneert de lijnnummerverschuiving van het [XmlReader](../xmlreader/) object. |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Retourneert de lijnpositieverschuiving van het [XmlReader](../xmlreader/) object. |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Retourneert een waarde die het maximaal toegestane aantal tekens in een document aangeeft dat ontstaat door het uitbreiden van entiteiten. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Retourneert een waarde die het maximaal toegestane aantal tekens in een XML-document aangeeft. Een nul (0) waarde betekent geen limiet voor de grootte van het XML-document. Een niet-nul waarde specificeert de maximale grootte, in tekens. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Retourneert de [XmlNameTable](../xmlnametable/) die wordt gebruikt voor geatomiseerde tekenreeksvergelijkingen. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Retourneert een waarde die aangeeft of verwerking van documenttype-definitie (DTD) verboden moet worden. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Retourneert de XmlSchemaSet die moet worden gebruikt bij het uitvoeren van schema-validatie. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Retourneert een waarde die de instellingen voor schemavalidatie aangeeft. Deze instelling is van toepassing op [XmlReader](../xmlreader/) objecten die schemas valideren ([XmlReaderSettings::get_ValidationType](./get_validationtype/) waarde is [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Retourneert een waarde die aangeeft of de [XmlReader](../xmlreader/) validatie of typetoewijzing zal uitvoeren tijdens het lezen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [Reset](./reset/)() | Reset de leden van de instellingenklasse naar hun standaardwaarden. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Stelt een waarde in die aangeeft of karaktercontrole moet worden uitgevoerd. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Stelt een waarde in die aangeeft of de onderliggende stream of TextReader moet worden gesloten wanneer de lezer wordt gesloten. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Stelt het conformiteitsniveau in waaraan de [XmlReader](../xmlreader/) zal voldoen. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Stelt een waarde in die de verwerking van DTD's bepaalt. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Stelt een waarde in die aangeeft of commentaren genegeerd moeten worden. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Stelt een waarde in die aangeeft of verwerkingsinstructies genegeerd moeten worden. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Stelt een waarde in die aangeeft of onbeduidende witruimte genegeerd moet worden. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Stelt de lijnnummerverschuiving van het [XmlReader](../xmlreader/) object in. |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Stelt de lijnpositieverschuiving van het [XmlReader](../xmlreader/) object in. |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Stelt een waarde in die het maximaal toelaatbare aantal tekens in een document aangeeft dat voortkomt uit het uitbreiden van entiteiten. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Stelt een waarde in die het maximaal toelaatbare aantal tekens in een XML-document aangeeft. Een nul (0) waarde betekent geen limiet voor de grootte van het XML-document. Een niet-nul waarde specificeert de maximale grootte, in tekens. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Stelt de [XmlNameTable](../xmlnametable/) in die wordt gebruikt voor geatomiseerde tekenreeksvergelijkingen. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Stelt een waarde in die aangeeft of verwerking van documenttype-definitie (DTD) verboden moet worden. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Stelt de XmlSchemaSet in die moet worden gebruikt bij het uitvoeren van schemavalidatie. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Stelt een waarde in die de instellingen voor schemavalidatie aangeeft. Deze instelling is van toepassing op [XmlReader](../xmlreader/) objecten die schemas valideren ([XmlReaderSettings::get_ValidationType](./get_validationtype/) waarde is [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Stelt een waarde in die aangeeft of de [XmlReader](../xmlreader/) validatie of typetoewijzing zal uitvoeren tijdens het lezen. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Stelt de [XmlResolver](../xmlresolver/) in die wordt gebruikt om externe documenten te benaderen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het mogelijk om aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Voegt een gebeurtenisafhandelaar toe die wordt uitgevoerd wanneer de lezer validatiefouten tegenkomt. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Verwijdert een gebeurtenisafhandelaar die wordt uitgevoerd wanneer de lezer validatiefouten tegenkomt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Initialiseert een nieuwe instantie van de [XmlReaderSettings](./) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor gedeelde pointer naar een instantie van deze klasse. |

## Opmerkingen

Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertie-fouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om het door te geven aan functies als argument. 

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)