---
title: InsertAutoShape()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu s použitím výchozího formátování šablony.
type: docs
weight: 339
url: /cs/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metoda

Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu s použitím výchozího formátování šablony.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit nový automatický tvar. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatického tvaru, který se má vložit. |
| x | **float** | X-souřadnice rámce tvaru, v bodech. |
| y | **float** | Y-souřadnice rámce tvaru, v bodech. |
| width | **float** | Šířka rámce tvaru, v bodech. |
| height | **float** | Výška rámce tvaru, v bodech. |

### Návratová hodnota

Nově vytvořený [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metoda

Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, případně jej inicializuje výchozím stylem šablony.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit automatický tvar. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatického tvaru, který se má vložit. |
| x | **float** | X-souřadnice rámce tvaru, v bodech. |
| y | **float** | Y-souřadnice rámce tvaru, v bodech. |
| width | **float** | Šířka rámce tvaru, v bodech. |
| height | **float** | Výška rámce tvaru, v bodech. |
| createFromTemplate | **bool** | True pro použití výchozího stylu šablony (včetně ne-prázdného názvu, jednoduchého stylu a centrovaného textu); false pro vytvoření tvaru se všemi vlastnostmi nastavenými na výchozí hodnoty. |

### Návratová hodnota

Nově vytvořený [IAutoShape](../../iautoshape/).

## Viz také

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)