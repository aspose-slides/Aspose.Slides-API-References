---
title: XmlSchemaGroupRef
second_title: Aspose.Slides voor C++ API-referentie
description: Representeert het group-element met ref-attribuut uit de XML Schema zoals gespecificeerd door de World Wide Web Consortium (W3C). Deze klasse wordt gebruikt binnen complexe types die een group refereren die op schema-niveau is gedefinieerd.
type: docs
weight: 456
url: /nl/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef klasse

Representeert het **group** element met **ref** attribuut uit de XML [Schema](../) zoals gespecificeerd door de World Wide [Web](../../system.web/) Consortium (W3C). Deze klasse wordt gebruikt binnen complexe types die een **group** refereren die op **schema** niveau is gedefinieerd.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```


## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Retourneert de **annotation** eigenschap. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Retourneert de string-id. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retourneert het regelnummer in het bestand waarnaar het **schema** element verwijst. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retourneert de regelpositie in het bestand waarnaar het **schema** element verwijst. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Retourneert het maximale aantal keren dat de Particle kan voorkomen. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Retourneert het getal als een string-waarde. Maximale aantal keren dat de Particle kan voorkomen. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Retourneert het minimale aantal keren dat de Particle kan voorkomen. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Retourneert het getal als een string-waarde. Het minimale aantal keren dat de Particle kan voorkomen. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retourneert de XmlSerializerNamespaces die gebruikt moet worden met dit schema-object. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retourneert de ouder van deze [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaGroupBase](../xmlschemagroupbase/)\> [get_Particle](./get_particle/)() | Retourneert een van de [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) of [XmlSchemaSequence](../xmlschemasequence/) klassen, die de post-compilatie interpretatie van de **Particle** waarde bevat. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Retourneert de naam van een groep gedefinieerd in dit schema (of een ander schema aangegeven door de opgegeven namespace). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retourneert de bronlocatie van het bestand dat het schema laadde. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Retourneert de gekwalificeerde attributen die niet tot de doel-namespace van het huidige schema behoren. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur geassocieerd met het object op. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Schakelt hashing van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakerobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Schakelt klonen van aangepaste types in. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel value-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Stelt de **annotation** eigenschap in. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Stelt de string-id in. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Stelt het regelnummer in het bestand in waarnaar het **schema** element verwijst. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Stelt de regelpositie in het bestand in waarnaar het **schema** element verwijst. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Stelt het maximale aantal keren in dat de Particle kan voorkomen. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Stelt het getal in als een string-waarde. Maximale aantal keren dat de Particle kan voorkomen. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Stelt het minimale aantal keren in dat de Particle kan voorkomen. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Stelt het getal in als een string-waarde. Het minimale aantal keren dat de Particle kan voorkomen. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Stelt de XmlSerializerNamespaces in die gebruikt moet worden met dit schema-object. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Stelt de ouder in van deze [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Stelt de naam in van een groep gedefinieerd in dit schema (of een ander schema aangegeven door de opgegeven namespace). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Stelt de bronlocatie in van het bestand dat het schema laadde. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Stelt de gekwalificeerde attributen in die niet tot de doel-namespace van het huidige schema behoren. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Schakelt het converteren van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakerobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlSchemaGroupRef](./xmlschemagroupref/)() | Initialiseert een nieuwe instantie van de [XmlSchemaGroupRef](./) klasse. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialiseert een nieuwe instantie van de [XmlSchemaObject](../xmlschemaobject/) klasse. |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Initialiseert een nieuwe instantie van de [XmlSchemaParticle](../xmlschemaparticle/) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |

## Opmerkingen

Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om hem als argument aan functies door te geven. 

## Zie ook

* Klasse [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Bibliotheek [Aspose.Slides](../../)