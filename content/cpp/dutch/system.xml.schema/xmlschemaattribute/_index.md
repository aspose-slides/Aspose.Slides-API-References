---
title: XmlSchemaAttribute
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het attribuut-element van het XML-schema voor, zoals gespecificeerd door het World Wide Web Consortium (W3C). Attributen bieden aanvullende informatie voor andere documentelementen. Het attribuut-tag staat genesteld tussen de tags van een document-element voor het schema. Het XML-document toont attributen als benoemde items in de openings-tag van een element.
type: docs
weight: 170
url: /nl/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute klasse


Vertegenwoordigt het **attribute**-element van de XML [Schema](../) zoals gespecificeerd door de World Wide [Web](../../system.web/) Consortium (W3C). Attributen bieden aanvullende informatie voor andere documentelementen. Het attribuuttag staat genest tussen de tags van een element van een document voor het schema. Het XML-document toont attributen als benoemde items in de openingstag van een element.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-kommapuntenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-kommapuntenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Retourneert de **annotation**-eigenschap. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_AttributeSchemaType](./get_attributeschematype/)() | Retourneert een [XmlSchemaSimpleType](../xmlschemasimpletype/)-object dat het type van het attribuut vertegenwoordigt op basis van de [XmlSchemaAttribute::get_SchemaType](./get_schematype/)- of [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/)-waarde van het attribuut. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_AttributeType](./get_attributetype/)() | Retourneert het object op basis van de [XmlSchemaAttribute::get_SchemaType](./get_schematype/)- of [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/)-waarde van het attribuut dat de post-compilatie-interpretatie van de **AttributeType**-waarde bevat. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Retourneert de standaardwaarde voor het attribuut. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Retourneert de vaste waarde voor het attribuut. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Retourneert de vorm voor het attribuut. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Retourneert de tekenreeks-id. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retourneert het regelnr. in het bestand waarnaar het **schema**-element verwijst. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retourneert de regelpositie in het bestand waarnaar het **schema**-element verwijst. |
| [String](../../system/string/) [get_Name](./get_name/)() | Retourneert de naam van het attribuut. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retourneert de XmlSerializerNamespaces die met dit schema-object moeten worden gebruikt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retourneert de ouder van deze [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Retourneert de gekwalificeerde naam voor het attribuut. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Retourneert de naam van een attribuut gedeclareerd in dit schema (of een ander schema aangegeven door de opgegeven namespace). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_SchemaType](./get_schematype/)() | Retourneert het attribuuttype naar een simpel type. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Retourneert de naam van het simpele type gedefinieerd in dit schema (of een ander schema aangegeven door de opgegeven namespace). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retourneert de bronlocatie voor het bestand dat het schema laadde. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Retourneert de gekwalificeerde attributen die niet tot de doel-namespace van het huidige schema behoren. |
| [XmlSchemaUse](../xmlschemause/) [get_Use](./get_use/)() | Retourneert informatie over hoe het attribuut wordt gebruikt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement-vergrendeling. Direct aanroepen of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert alleen nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referentie-vergelijkt waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met opgegeven waarde. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Stelt de **annotation**-eigenschap in. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Stelt de standaardwaarde voor het attribuut in. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Stelt de vaste waarde voor het attribuut in. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Stelt de vorm voor het attribuut in. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Stelt de tekenreeks-id in. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Stelt het regelnr. in het bestand waarnaar het **schema**-element verwijst, in. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Stelt de regelpositie in het bestand waarnaar het **schema**-element verwijst, in. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Stelt de naam van het attribuut in. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Stelt de XmlSerializerNamespaces in die met dit schema-object moeten worden gebruikt. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Stelt de ouder van deze [XmlSchemaObject](../xmlschemaobject/) in. |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Stelt de naam van een attribuut gedeclareerd in dit schema (of een ander schema aangegeven door de opgegeven namespace) in. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | Stelt het attribuuttype in op een simpel type. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Stelt de naam van het simpele type gedefinieerd in dit schema (of een ander schema aangegeven door de opgegeven namespace) in. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Stelt de bronlocatie voor het bestand dat het schema laadde, in. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Stelt de gekwalificeerde attributen in die niet tot de doel-namespace van het huidige schema behoren. |
| void [set_Use](./set_use/)([XmlSchemaUse](../xmlschemause/)) | Stelt informatie over hoe het attribuut wordt gebruikt, in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel n-de sjabloon-argument in als een zwakke pointer (in plaats van gedeelde). Maakt het schakelen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement-ontgrendeling. Direct aanroepen of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlSchemaAttribute](./xmlschemaattribute/)() | Initialiseert een nieuwe instantie van de [XmlSchemaAttribute](./)-klasse. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialiseert een nieuwe instantie van de [XmlSchemaObject](../xmlschemaobject/)-klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijgeeft alle interne datastructuren. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |
## Opmerkingen



Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Plaats deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om deze door te geven aan functies als argument. 

## Zie ook

* Klasse [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)