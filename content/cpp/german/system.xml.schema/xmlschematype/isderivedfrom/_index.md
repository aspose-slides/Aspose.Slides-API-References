---
title: IsDerivedFrom()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt einen Wert zurück, der angibt, ob der angegebene abgeleitete Schematausdruck vom angegebenen Basisschematausdruck abgeleitet ist.
type: docs
weight: 209
url: /de/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) Methode


Gibt einen Wert zurück, der angibt, ob der angegebene abgeleitete Schematausdruck vom angegebenen Basisschematausdruck abgeleitet ist.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Der zu testende abgeleitete [XmlSchemaType](../). |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Der Basistyp [XmlSchemaType](../), gegen den der abgeleitete [XmlSchemaType](../) geprüft wird. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Einer der Werte von XmlSchemaDerivationMethod, der eine Typableitungsmethode darstellt, die vom Test ausgeschlossen werden soll. |

### Rückgabewert

**true**, wenn der abgeleitete Typ vom Basistyp abgeleitet ist; andernfalls **false**.

## Siehe auch

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaType](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)