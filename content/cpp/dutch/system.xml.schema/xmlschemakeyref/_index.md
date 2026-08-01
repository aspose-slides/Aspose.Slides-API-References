---
title: XmlSchemaKeyref
second_title: Aspose.Slides voor C++ API-referentie
description: Deze klasse vertegenwoordigt het keyref-element van XMLSchema zoals gespecificeerd door het World Wide Web Consortium (W3C).
type: docs
weight: 547
url: /nl/system.xml.schema/xmlschemakeyref/
---
## XmlSchemaKeyref klasse


Deze klasse vertegenwoordigt het **keyref** element van XMLSchema zoals gespecificeerd door het World Wide [Web](../../system.web/) Consortium (W3C).

```cpp
class XmlSchemaKeyref : public System::Xml::Schema::XmlSchemaIdentityConstraint
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Retourneert de **annotation** eigenschap. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Fields](../xmlschemaidentityconstraint/get_fields/)() | Retourneert de collectie velden die als kinderen gelden voor de XML Path Language ([XPath](../../system.xml.xpath/)) expressieselector. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Retourneert de tekenreeks-id. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retourneert het regelnummer in het bestand waarnaar het **schema** element verwijst. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retourneert de regelpositie in het bestand waarnaar het **schema** element verwijst. |
| [String](../../system/string/) [get_Name](../xmlschemaidentityconstraint/get_name/)() | Retourneert de naam van de identiteitbeperking. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retourneert de XmlSerializerNamespaces die met dit schema-object moeten worden gebruikt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retourneert de ouder van dit [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschemaidentityconstraint/get_qualifiedname/)() | Retourneert de gekwalificeerde naam van de identiteitbeperking, die de post-compilatie interpretatie van de **QualifiedName** waarde bevat. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Refer](./get_refer/)() | Retourneert de naam van de sleutel waarnaar deze beperking verwijst in een ander eenvoudig of complex type. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaXPath](../xmlschemaxpath/)\> [get_Selector](../xmlschemaidentityconstraint/get_selector/)() | Retourneert het [XPath](../../system.xml.xpath/) expressie **selector** element. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retourneert de bronlocatie van het bestand dat het schema heeft geladen. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Retourneert de gekwalificeerde attributen die niet tot de doel-namespace van het huidige schema behoren. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analog van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) wachtobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Stelt de **annotation** eigenschap in. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Stelt de tekenreeks-id in. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Stelt het regelnummer in het bestand in waarnaar het **schema** element verwijst. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Stelt de regelpositie in het bestand in waarnaar het **schema** element verwijst. |
| void [set_Name](../xmlschemaidentityconstraint/set_name/)(const [String](../../system/string/)\&) | Stelt de naam van de identiteitbeperking in. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Stelt de XmlSerializerNamespaces in die met dit schema-object moeten worden gebruikt. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Stelt de ouder van deze [XmlSchemaObject](../xmlschemaobject/) in. |
| void [set_Refer](./set_refer/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Stelt de naam van de sleutel in waarnaar deze beperking verwijst in een ander eenvoudig of complex type. |
| void [set_Selector](../xmlschemaidentityconstraint/set_selector/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaXPath](../xmlschemaxpath/)\>\&) | Stelt het [XPath](../../system.xml.xpath/) expressie **selector** element in. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Stelt de bronlocatie in van het bestand dat het schema heeft geladen. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Stelt de gekwalificeerde attributen in die niet tot de doel-namespace van het huidige schema behoren. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Vermindert en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachtobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Vermindert de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/xmlschemaidentityconstraint/)() | Initialiseert een nieuw exemplaar van de [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/) klasse. |
|  [XmlSchemaKeyref](./xmlschemakeyref/)() | Initialiseert een nieuw exemplaar van de [XmlSchemaKeyref](./) klasse. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialiseert een nieuw exemplaar van de [XmlSchemaObject](../xmlschemaobject/) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een exemplaar van deze klasse. |

## Opmerkingen



Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit exemplaren van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven. 

## Zie ook

* Klasse [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/)
* Naamruimte [System::Xml::Schema](../)
* Bibliotheek [Aspose.Slides](../../)