---
title: XmlSchemaAnnotation
second_title: Aspose.Slides voor C++ API Referentie
description: Representeert het World Wide Web Consortium (W3C) annotatie-element.
type: docs
weight: 118
url: /nl/system.xml.schema/xmlschemaannotation/
---
## XmlSchemaAnnotation klasse

Representeert het World Wide [Web](../../system.web/) Consortium (W3C) **annotatie** element.

```cpp
class XmlSchemaAnnotation : public System::Xml::Schema::XmlSchemaObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl floating-point vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl floating-point vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [String](../../system/string/) [get_Id](./get_id/)() | Retourneert de string-id. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | Retourneert de **Items** collectie die wordt gebruikt om de **appinfo** en **documentation** kind-elementen op te slaan. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retourneert het regelnummmer in het bestand waar het **schema**-element naar verwijst. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retourneert de regelpositie in het bestand waar het **schema**-element naar verwijst. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retourneert de XmlSerializerNamespaces die gebruikt dient te worden met dit schema-object. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retourneert de ouder van deze [XmlSchemaObject](../xmlschemaobject/). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retourneert de bronlocatie voor het bestand dat het schema laadde. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | Retourneert de gekwalificeerde attributen die niet behoren tot de doelnamespace van het schema. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-berekening van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van C# lock() statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt per referentie waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | Stelt de string-id in. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Stelt het regelnummmer in het bestand in waar het **schema**-element naar verwijst. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Stelt de regelpositie in het bestand in waar het **schema**-element naar verwijst. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Stelt de XmlSerializerNamespaces in die met dit schema-object gebruikt moet worden. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Stelt de ouder in van deze [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Stelt de bronlocatie in voor het bestand dat het schema laadde. |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Stelt de gekwalificeerde attributen in die niet behoren tot de doelnamespace van het schema. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Stelt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert ontgrendeling van C# lock() statement. Roep rechtstreeks aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlSchemaAnnotation](./xmlschemaannotation/)() | Initialiseert een nieuwe instantie van de [XmlSchemaAnnotation](./) klasse. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialiseert een nieuwe instantie van de [XmlSchemaObject](../xmlschemaobject/) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een shared pointer naar een instantie van deze klasse. |

## Opmerkingen

Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om het als argument aan functies door te geven. 

## Zie ook

* Klasse [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Bibliotheek [Aspose.Slides](../../)