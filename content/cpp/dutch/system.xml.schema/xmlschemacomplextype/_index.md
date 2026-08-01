---
title: XmlSchemaComplexType
second_title: Aspose.Slides voor C++ API-referentie
description: Representeert het complexType element uit XML-schema zoals gespecificeerd door het World Wide Web Consortium (W3C). Deze klasse definieert een complex type dat de set van attributen en de inhoud van een element bepaalt.
type: docs
weight: 300
url: /nl/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType klasse


Representeert het **complexType**-element uit XML [Schema](../) zoals gespecificeerd door het World Wide [Web](../../system.web/) Consortium (W3C). Deze klasse definieert een complex type dat de reeks attributen en inhoud van een element bepaalt.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Retourneert de **annotation** eigenschap. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | Retourneert de waarde voor het [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-component van het complexe type. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | Retourneert de verzameling attributen voor het complexe type. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | Retourneert de verzameling van alle samengevoegde attributen van dit complexe type en zijn basistypen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | Retourneert de post-compilatie-waarde voor **anyAttribute** voor dit complexe type en zijn basistype(s). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | Retourneert het objecttype na compilatie of het ingebouwde XML [Schema](../) Definition Language (XSD) gegevenstype, simpleType-element of complexType-element. Dit is een infoset-waarde na schema-compilatie. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | Retourneert de post-compilatie-waarde voor het basistype van dit schema-type. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Retourneert het **block** attribuut. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Retourneert de waarde nadat het type is gecompileerd naar de post-schema-validatie-informatieset (infoset). Deze waarde geeft aan hoe het type wordt afgedwongen wanneer **xsi:type** wordt gebruikt in het instantiedocument. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | Retourneert de post-compilatie-[XmlSchemaContentModel](../xmlschemacontentmodel/) van dit complexe type. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | Retourneert het contentmodel van het complexe type dat de post-compilatie-waarde bevat. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | Retourneert het particle dat de post-compilatie-waarde van het [XmlSchemaComplexType::get_ContentType](./get_contenttype/)-particle bevat. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | Retourneert de post-compilatie-waarde voor het gegevenstype van het complexe type. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | Retourneert de post-compilatie-informatie over hoe dit element is afgeleid van zijn basistype. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | Retourneert het uiteindelijke attribuut van de type-afleiding dat aangeeft of verdere afleidingen toegestaan zijn. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | Retourneert de post-compilatie-interpretatie van de [XmlSchemaType::get_Final](../xmlschematype/get_final/)-waarde. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Retourneert de tekenreeks-id. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Retourneert de informatie die bepaalt of het **complexType**-element kan worden gebruikt in het instantiedocument. |
| **bool** [get_IsMixed](./get_ismixed/)() override | Retourneert informatie die bepaalt of het complexe type een gemengd contentmodel heeft (opmaak binnen de inhoud). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retourneert het regelsnummer in het bestand waarnaar het **schema**-element verwijst. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retourneert de regelpositie in het bestand waarnaar het **schema**-element verwijst. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | Retourneert de naam van het type. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retourneert de XmlSerializerNamespaces die met dit schema-object gebruikt moet worden. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retourneert de ouder van deze [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | Retourneert het compositor-type als een van de [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) of [XmlSchemaSequence](../xmlschemasequence/)-klassen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | Retourneert de gekwalificeerde naam voor het type dat is opgebouwd uit het **Name**-attribuut van dit type. Dit is een post-schema-compilatie-waarde. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retourneert de bronlocatie van het bestand dat het schema heeft geladen. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | Retourneert de XmlTypeCode van het type. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Retourneert de gekwalificeerde attributen die niet tot de doel-namespace van het huidige schema behoren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Retourneert een [XmlSchemaComplexType](./) die het ingebouwde complexe type van het gespecificeerde complexe type vertegenwoordigt. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Retourneert een [XmlSchemaComplexType](./) die het ingebouwde complexe type van het complexe type vertegenwoordigt dat wordt gespecificeerd door een gekwalificeerde naam. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Retourneert een [XmlSchemaSimpleType](../xmlschemasimpletype/) die het ingebouwde eenvoudige type van het eenvoudige type vertegenwoordigt dat wordt gespecificeerd door de gekwalificeerde naam. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Retourneert een [XmlSchemaSimpleType](../xmlschemasimpletype/) die het ingebouwde eenvoudige type van het opgegeven eenvoudige type vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C# ‘is’-operator. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Retourneert een waarde die aangeeft of het opgegeven afgeleide schema-type is afgeleid van het opgegeven basistype. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt waardetype-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Stelt de **annotation** eigenschap in. |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | Stelt de waarde in voor het [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-component van het complexe type. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Stelt het **block** attribuut in. |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | Stelt de post-compilatie-[XmlSchemaContentModel](../xmlschemacontentmodel/) van dit complexe type in. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Stelt het uiteindelijke attribuut van de type-afleiding in dat aangeeft of verdere afleidingen toegestaan zijn. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Stelt de tekenreeks-id in. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Stelt de informatie in die bepaalt of het **complexType**-element kan worden gebruikt in het instantiedocument. |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | Stelt informatie in die bepaalt of het complexe type een gemengd contentmodel heeft (opmaak binnen de inhoud). |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Stelt het regelsnummer in in het bestand waarnaar het **schema**-element verwijst. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Stelt de regelpositie in in het bestand waarnaar het **schema**-element verwijst. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | Stelt de naam van het type in. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Stelt de XmlSerializerNamespaces in die met dit schema-object gebruikt moet worden. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Stelt de ouder van deze [XmlSchemaObject](../xmlschemaobject/) in. |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | Stelt het compositor-type in als een van de [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) of [XmlSchemaSequence](../xmlschemasequence/)-klassen. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Stelt de bronlocatie van het bestand dat het schema heeft geladen in. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Stelt de gekwalificeerde attributen in die niet tot de doel-namespace van het huidige schema behoren. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloon-argument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers te schakelen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | Initialiseert een nieuw exemplaar van de [XmlSchemaComplexType](./) klasse. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialiseert een nieuw exemplaar van de [XmlSchemaObject](../xmlschemaobject/) klasse. |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | Initialiseert een nieuw exemplaar van de [XmlSchemaType](../xmlschematype/) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |
## Opmerkingen



Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten kan veroorzaken. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies te geven. 

## Zie ook

* Class [XmlSchemaType](../xmlschematype/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)