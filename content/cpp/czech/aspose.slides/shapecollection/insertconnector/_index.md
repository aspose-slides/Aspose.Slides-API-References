---
title: InsertConnector()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří nový tvar spojky a vloží jej do kolekce tvarů na zadaném indexu, přičemž použije výchozí styl šablony.
type: docs
weight: 430
url: /cs/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metoda


Vytvoří nový tvar spojky a vloží jej do kolekce tvarů na zadaném indexu, přičemž použije výchozí styl šablony.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se vloží tvar spojky. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) tvaru spojky, která se má vložit. |
| x | **float** | Souřadnice x rámce spojky v bodech. |
| y | **float** | Souřadnice y rámce spojky v bodech. |
| width | **float** | Šířka rámce spojky v bodech. |
| height | **float** | Výška rámce spojky v bodech. |

### Návratová hodnota

Nově vytvořený [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metoda


Vytvoří nový tvar spojky a vloží jej do kolekce tvarů na zadaném indexu, volitelně použije výchozí styl šablony.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se vloží tvar spojky. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) tvaru spojky, která se má vložit. |
| x | **float** | Souřadnice x rámce spojky v bodech. |
| y | **float** | Souřadnice y rámce spojky v bodech. |
| width | **float** | Šířka rámce spojky v bodech. |
| height | **float** | Výška rámce spojky v bodech. |
| createFromTemplate | **bool** | True pro použití výchozího stylu šablony (neprázdný název, jednoduchý styl); false pro vytvoření spojky s výchozími hodnotami vlastností. |

### Návratová hodnota

Nově vytvořený [IConnector](../../iconnector/).

## Viz také

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)