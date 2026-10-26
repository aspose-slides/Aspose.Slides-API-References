---
title: IsDerivedFrom()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett värde som anger om den angivna avledda schematypen är avledd från den angivna bas-schematypen.
type: docs
weight: 209
url: /sv/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) method

Returnerar ett värde som anger om den angivna avledda schematypen är avledd från den angivna bas-schematypen.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Den avledda [XmlSchemaType](../) att testa. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Den bas [XmlSchemaType](../) för att testa den avledda [XmlSchemaType](../) mot. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | En av XmlSchemaDerivationMethod-värdena som representerar en typavledningsmetod att undanta från testning. |

### Returvärde

**true** om den avledda typen är avledd från bas-typen; annars **false**.

## Se även

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchemaType](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)