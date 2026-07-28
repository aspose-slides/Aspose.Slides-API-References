---
title: IsDerivedFrom()
second_title: Aspose.Slides C++ API referenciája
description: Visszaad egy értéket, amely jelzi, hogy a megadott származtatott séma típus származik-e a megadott alapséma típusból.
type: docs
weight: 209
url: /hu/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) metódus


Visszaad egy értéket, amely jelzi, hogy a megadott származtatott sématípus származik-e a megadott alapsématípusból.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | A tesztelendő származtatott [XmlSchemaType](../). |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Az alap [XmlSchemaType](../) a származtatott [XmlSchemaType](../) ellenőrzéséhez. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Az XmlSchemaDerivationMethod értékek egyike, amely egy típus származtatási módszert jelöl, amelyet ki kell zárni a tesztelésből. |

### Visszatérési érték

**true**, ha a származtatott típus származik az alaptípusból; egyébként **false**.

## Lásd még

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)