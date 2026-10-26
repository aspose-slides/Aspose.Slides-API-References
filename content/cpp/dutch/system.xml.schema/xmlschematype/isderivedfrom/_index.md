---
title: IsDerivedFrom()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een waarde die aangeeft of het opgegeven afgeleide schematype is afgeleid van het opgegeven basistype.
type: docs
weight: 209
url: /nl/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) methode

Retourneert een waarde die aangeeft of het opgegeven afgeleide schematype is afgeleid van het opgegeven basistype.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | De afgeleide [XmlSchemaType](../) om te testen. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | De basis [XmlSchemaType](../) om de afgeleide [XmlSchemaType](../) tegen te testen. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Een van de XmlSchemaDerivationMethod waarden die een type-afleidingsmethode vertegenwoordigen die moet worden uitgesloten van testen. |

### Retourwaarde

**true** if the derived type is derived from the base type; otherwise, **false**.

## Zie ook

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaType](../)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)