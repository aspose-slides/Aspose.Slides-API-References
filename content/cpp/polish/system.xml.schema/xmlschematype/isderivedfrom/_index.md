---
title: IsDerivedFrom()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca wartość wskazującą, czy określony typ schematu pochodnego jest pochodny od określonego typu schematu bazowego.
type: docs
weight: 209
url: /pl/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) metoda

Zwraca wartość wskazującą, czy określony typ schematu pochodnego jest pochodny od określonego typu schematu bazowego.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Pochodny [XmlSchemaType](../) do przetestowania. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Podstawowy [XmlSchemaType](../) do przetestowania pochodnego [XmlSchemaType](../). |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Jedna z wartości XmlSchemaDerivationMethod reprezentująca metodę dziedziczenia typu, którą należy wykluczyć z testowania. |

### Wartość zwracana

**true** jeśli typ pochodny jest pochodny od typu bazowego; w przeciwnym razie **false**.

## Zobacz także

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)