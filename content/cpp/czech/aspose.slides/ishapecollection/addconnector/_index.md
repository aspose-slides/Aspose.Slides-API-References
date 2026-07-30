---
title: AddConnector()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový tvar spojky s výchozím stylováním šablony a přidá jej na konec kolekce tvarů.
type: docs
weight: 378
url: /cs/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) method


Vytvoří nový tvar spojky s výchozím stylováním šablony a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Typ [ShapeType](../../shapetype/) tvaru spojky, který se má přidat. |
| x | **float** | x-souřadnice rámce spojky v bodech. |
| y | **float** | y-souřadnice rámce spojky v bodech. |
| width | **float** | Šířka rámce spojky v bodech. |
| height | **float** | Výška rámce spojky v bodech. |

### Návratová hodnota

Nově vytvořený [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method


Vytvoří nový tvar spojky a přidá jej na konec kolekce tvarů, volitelně použije výchozí stylování šablony.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Typ [ShapeType](../../shapetype/) tvaru spojky, který se má vytvořit. |
| x | **float** | x-souřadnice rámce spojky v bodech. |
| y | **float** | y-souřadnice rámce spojky v bodech. |
| width | **float** | Šířka rámce spojky v bodech. |
| height | **float** | Výška rámce spojky v bodech. |
| createFromTemplate | **bool** | True pro použití výchozího stylování šablony (neprázdný název, jednoduchý styl); false pro vytvoření spojky s výchozími hodnotami vlastností. |

### Návratová hodnota

Nově vytvořený [IConnector](../../iconnector/).

## Viz také

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IConnector](../../iconnector/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)