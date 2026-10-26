---
title: AddAutoShape()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů.
type: docs
weight: 352
url: /cs/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metoda

Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatického tvaru, který se má přidat. |
| x | **float** | Souřadnice x rámce tvaru, v bodech. |
| y | **float** | Souřadnice y rámce tvaru, v bodech. |
| width | **float** | Šířka rámce tvaru, v bodech. |
| height | **float** | Výška rámce tvaru, v bodech. |

### Návratová hodnota

Nově vytvořený [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metoda

Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, případně jej inicializuje výchozím formátováním šablony.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatického tvaru, který se má přidat. |
| x | **float** | Souřadnice x rámce tvaru, v bodech. |
| y | **float** | Souřadnice y rámce tvaru, v bodech. |
| width | **float** | Šířka rámce tvaru, v bodech. |
| height | **float** | Výška rámce tvaru, v bodech. |
| createFromTemplate | **bool** | True, pokud se má na nový tvar použít výchozí styl šablony (jednoduchý styl, centrovaný text a neprázdný název); false, pokud se má tvar vytvořit se všemi vlastnostmi nastavenými na jejich výchozí hodnoty. |

### Návratová hodnota

Nově vytvořený [IAutoShape](../../iautoshape/).

## Viz také

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)