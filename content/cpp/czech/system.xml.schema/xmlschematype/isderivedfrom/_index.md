---
title: IsDerivedFrom()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací hodnotu, která udává, zda je zadaný odvozený typ schématu od zadaného základního typu schématu.
type: docs
weight: 209
url: /cs/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) method


Vrací hodnotu, která udává, zda je zadaný odvozený typ schématu od zadaného základního typu schématu.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Odvozený [XmlSchemaType](../) k testování. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Základní [XmlSchemaType](../) pro testování odvozeného [XmlSchemaType](../). |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Jedna z hodnot XmlSchemaDerivationMethod představující metodu odvození typu, kterou je třeba z testování vyloučit. |

### Návratová hodnota

**true** pokud je odvozený typ od základního typu; jinak **false**.

## Viz také

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlSchemaType](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)