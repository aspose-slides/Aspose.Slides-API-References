---
title: XmlSchemaDatatype
second_title: Aspose.Slides voor C++ API-referentie
description: De XmlSchemaDatatype-klasse is een abstracte klasse voor het mappen van XML Schema definitietaal (XSD)-typen naar runtime-typen.
type: docs
weight: 339
url: /nl/system.xml.schema/xmlschemadatatype/
---
## XmlSchemaDatatype klasse


The [XmlSchemaDatatype](./) class is an abstract class for mapping XML [Schema](../) definition language (XSD) types to runtime types.

```cpp
class XmlSchemaDatatype : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ChangeType](./changetype/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) | Converteert de opgegeven waarde, waarvan het type een van de geldige representaties is van het XML-schema-type vertegenwoordigd door de [XmlSchemaDatatype](./), naar het opgegeven runtime-type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ChangeType](./changetype/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Converteert de opgegeven waarde, waarvan het type een van de geldige representaties is van het XML-schema-type vertegenwoordigd door de [XmlSchemaDatatype](./), naar het opgegeven runtime-type met gebruik van de [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) als de [XmlSchemaDatatype](./) het **xs:QName**-type representeert of een daarvan afgeleid type. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert zwevend-punt-vergelijking in C#-stijl waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel NaN volgens IEC 60559:1989 niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert zwevend-punt-vergelijking in C#-stijl waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel NaN volgens IEC 60559:1989 niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [XmlTokenizedType](../../system.xml/xmltokenizedtype/) [get_TokenizedType](./get_tokenizedtype/)() | Wordt, wanneer hij wordt overschreven in een afgeleide klasse, het type voor de **string** opgehaald zoals gespecificeerd in de World Wide [Web](../../system.web/) Consortium (W3C) XML 1.0-specificatie. |
| virtual [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | Retourneert de XmlTypeCode-waarde voor het eenvoudige type. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Wordt, wanneer hij wordt overschreven in een afgeleide klasse, het type van het item opgehaald. |
| virtual [XmlSchemaDatatypeVariety](../xmlschemadatatypevariety/) [get_Variety](./get_variety/)() | Retourneert de XmlSchemaDatatypeVariety-waarde voor het eenvoudige type. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-berekening van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het door targetType beschreven type is. Analoge van de C# 'is'-operator. |
| virtual **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](./)\>) | Deze methode retourneert altijd **false**. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-wachtoject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt kloonvorming van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ParseValue](./parsevalue/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Wordt, wanneer hij wordt overschreven in een afgeleide klasse, de opgegeven **string** gevalideerd tegen een ingebouwd of door de gebruiker gedefinieerd eenvoudig type. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert ontgrendeling van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-wachtoject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een shared pointer naar een instantie van deze klasse. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Xml::Schema](../)
* Bibliotheek [Aspose.Slides](../../)