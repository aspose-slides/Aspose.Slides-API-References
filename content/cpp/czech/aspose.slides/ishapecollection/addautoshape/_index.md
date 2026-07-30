---
title: AddAutoShape()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří novou automatickou tvaru s výchozím formátováním a přidá ji na konec kolekce tvarů.
type: docs
weight: 313
url: /cs/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method

Vytvoří novou automatickou tvaru s výchozím formátováním a přidá ji na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatického tvaru, který se má přidat. |
| x | **float** | X-souřadnice rámce tvaru, v bodech. |
| y | **float** | Y-souřadnice rámce tvaru, v bodech. |
| width | **float** | Šířka rámce tvaru, v bodech. |
| height | **float** | Výška rámce tvaru, v bodech. |

### Návratová hodnota

Nově vytvořený [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method

Vytvoří novou automatickou tvaru a přidá ji na konec kolekce tvarů, případně ji inicializuje výchozím formátováním šablony.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatického tvaru, který se má přidat. |
| x | **float** | X-souřadnice rámce tvaru, v bodech. |
| y | **float** | Y-souřadnice rámce tvaru, v bodech. |
| width | **float** | Šířka rámce tvaru, v bodech. |
| height | **float** | Výška rámce tvaru, v bodech. |
| createFromTemplate | **bool** | True, pokud se má na nový tvar použít výchozí styl šablony (jednoduchý styl, zarovnaný text a nepustý název); false, pokud se má vytvořit tvar se všemi vlastnostmi nastavenými na výchozí hodnoty. |

### Návratová hodnota

Nově vytvořený [IAutoShape](../../iautoshape/).

## Viz také

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)