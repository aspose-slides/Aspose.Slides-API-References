---
title: InsertConnector()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový tvar spojky a vloží jej do kolekce tvarů na určeném indexu s použitím výchozího stylu šablony.
type: docs
weight: 391
url: /cs/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metoda

Vytvoří nový tvar spojky a vloží jej do kolekce tvarů na určeném indexu s použitím výchozího stylu šablony.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se má vložit tvar spojky. |
| shapeType | [ShapeType](../../shapetype/) | Typ [ShapeType](../../shapetype/) spojky, která se má vložit. |
| x | **float** | Souřadnice x rámce spojky, v bodech. |
| y | **float** | Souřadnice y rámce spojky, v bodech. |
| width | **float** | Šířka rámce spojky, v bodech. |
| height | **float** | Výška rámce spojky, v bodech. |

### Návratová hodnota

Nově vytvořený [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metoda

Vytvoří nový tvar spojky a vloží jej do kolekce tvarů na určeném indexu, volitelně s použitím výchozího stylu šablony.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se má vložit tvar spojky. |
| shapeType | [ShapeType](../../shapetype/) | Typ [ShapeType](../../shapetype/) spojky, která se má vložit. |
| x | **float** | Souřadnice x rámce spojky, v bodech. |
| y | **float** | Souřadnice y rámce spojky, v bodech. |
| width | **float** | Šířka rámce spojky, v bodech. |
| height | **float** | Výška rámce spojky, v bodech. |
| createFromTemplate | **bool** | True pro použití výchozího stylu šablony (neprázdný název, jednoduchý styl); false pro vytvoření spojky s výchozími hodnotami vlastností. |

### Návratová hodnota

Nově vytvořený [IConnector](../../iconnector/).

## Viz také

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IConnector](../../iconnector/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)