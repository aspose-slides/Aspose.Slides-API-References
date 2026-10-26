---
title: XmlSchemaElement
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt het element element uit een XML-schema zoals gespecificeerd door het World Wide Web Consortium (W3C). Deze klasse is de basisklasse voor alle deeltjes-types en wordt gebruikt om een element in een XML-document te beschrijven.
type: docs
weight: 365
url: /nl/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement klasse

Represents the **element** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). Deze klasse is de basisklasse voor alle deeltjes-typen en wordt gebruikt om een element in een XML-document te beschrijven.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Vergelijkt waarde-type objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Imiteert C#-stijl drijvende-kommapunten-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Imiteert C#-stijl drijvende-kommapunten-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Alleen voor intern gebruik. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Geeft de **annotation**-eigenschap terug. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Geeft een **Block**-afleiding terug. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Geeft de post-compilatie-interpretatie van de **Block**-waarde terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | Geeft de verzameling van beperkingen op het element terug. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Geeft de standaardwaarde van het element terug als de inhoud een eenvoudig type is of de inhoud van het element **textOnly** is. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | Geeft een [XmlSchemaType](../xmlschematype/)-object terug dat het type van het element vertegenwoordigt op basis van de [XmlSchemaElement::get_SchemaType](./get_schematype/)- of [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/)-waarden van het element. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | Geeft een object terug op basis van de [XmlSchemaElement](./)- of [XmlSchemaElement](./)-waarde van het element, die de post-compilatie-interpretatie van de **ElementType**-waarde bevat. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Geeft de **Final**-waarde terug om aan te geven dat geen verdere afleidingen zijn toegestaan. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Geeft de post-compilatie-interpretatie van de **Final**-waarde terug. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Geeft de vaste waarde terug. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Geeft het formulier voor het element terug. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Geeft de tekenreeks-id terug. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Geeft informatie terug die aangeeft of het element kan worden gebruikt in een instantiedocument. |
| **bool** [get_IsNillable](./get_isnillable/)() | Geeft informatie terug die aangeeft of **xsi:nil** kan voorkomen in de instantiedata. Duidt aan of een expliciete nil-waarde aan het element kan worden toegewezen. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Geeft het regelnr. in het bestand waaraan het **schema**-element verwijst terug. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Geeft de regelpositie in het bestand waaraan het **schema**-element verwijst terug. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Geeft het maximumaantal keer terug dat het deeltje kan voorkomen. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Geeft het getal als een tekenreeks terug. Maximumaantal keer dat het deeltje kan voorkomen. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Geeft het minimumaantal keer terug dat het deeltje kan voorkomen. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Geeft het getal als een tekenreeks terug. Het minimumaantal keer dat het deeltje kan voorkomen. |
| [String](../../system/string/) [get_Name](./get_name/)() | Geeft de naam van het element terug. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Geeft de XmlSerializerNamespaces terug die voor dit schema-object moet worden gebruikt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Geeft de ouder van deze [XmlSchemaObject](../xmlschemaobject/) terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Geeft de daadwerkelijke gekwalificeerde naam voor het opgegeven element terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Geeft de referentienaam van een element terug dat in dit schema (of een ander schema aangegeven door de opgegeven namespace) is gedeclareerd. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | Geeft het type van het element terug. Dit kan een complex type of een eenvoudig type zijn. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Geeft de naam van een ingebouwd gegevenstype terug dat in dit schema of een ander schema aangegeven door de opgegeven namespace is gedefinieerd. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Geeft de bronlocatie van het bestand dat het schema heeft geladen terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | Geeft de naam van een element terug dat door dit element wordt vervangen. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Geeft de gekwalificeerde attributen terug die niet tot de doel-namespace van het huidige schema behoren. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-generatie voor aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de vergrendeling van de C# lock() instructie. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | Kopieer-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Vergelijkt een waarde-type object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Stelt de **annotation**-eigenschap in. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Stelt een **Block**-afleiding in. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Stelt de standaardwaarde van het element in als de inhoud een eenvoudig type is of de inhoud van het element **textOnly** is. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Stelt de **Final**-waarde in om aan te geven dat geen verdere afleidingen zijn toegestaan. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Stelt de vaste waarde in. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Stelt het formulier voor het element in. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Stelt de tekenreeks-id in. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Stelt informatie in die aangeeft of het element kan worden gebruikt in een instantiedocument. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | Stelt informatie in die aangeeft of **xsi:nil** kan voorkomen in de instantiedata. Duidt aan of een expliciete nil-waarde aan het element kan worden toegewezen. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Stelt het regelnr. in het bestand waarnaar het **schema**-element verwijst in. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Stelt de regelpositie in het bestand waarnaar het **schema**-element verwijst in. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Stelt het maximumaantal keer in dat het deeltje kan voorkomen. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Stelt het getal in als een tekenreeks. Maximumaantal keer dat het deeltje kan voorkomen. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Stelt het minimumaantal keer in dat het deeltje kan voorkomen. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Stelt het getal in als een tekenreeks. Het minimumaantal keer dat het deeltje kan voorkomen. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Stelt de naam van het element in. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Stelt de XmlSerializerNamespaces in die voor dit schema-object moet worden gebruikt. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Stelt de ouder van deze [XmlSchemaObject](../xmlschemaobject/) in. |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Stelt de referentienaam in van een element dat in dit schema (of een ander schema aangegeven door de opgegeven namespace) is gedeclareerd. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Stelt het type van het element in. Dit kan een complex type of een eenvoudig type zijn. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Stelt de naam in van een ingebouwd gegevenstype dat in dit schema of een ander schema aangegeven door de opgegeven namespace is gedefinieerd. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Stelt de bronlocatie van het bestand dat het schema heeft geladen in. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Stelt de naam in van een element dat door dit element wordt vervangen. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Stelt de gekwalificeerde attributen in die niet tot de doel-namespace van het huidige schema behoren. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar een string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock() instructie. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlSchemaElement](./xmlschemaelement/)() | Initialiseert een nieuwe instantie van de [XmlSchemaElement](./) klasse. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initialiseert een nieuwe instantie van de [XmlSchemaObject](../xmlschemaobject/) klasse. |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Initialiseert een nieuwe instantie van de [XmlSchemaParticle](../xmlschemaparticle/) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |

## Opmerkingen

Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. 

## Zie ook

* Klasse [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)