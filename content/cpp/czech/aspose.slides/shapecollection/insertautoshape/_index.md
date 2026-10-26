---
title: InsertAutoShape()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, přičemž použije výchozí formátování šablony.
type: docs
weight: 378
url: /cs/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metoda

Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, přičemž použije výchozí formátování šablony.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se má vložit nový automatický tvar. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatického tvaru, který se má vložit. |
| x | **float** | x-souřadnice rámce tvaru, v bodech. |
| y | **float** | y-souřadnice rámce tvaru, v bodech. |
| width | **float** | šířka rámce tvaru, v bodech. |
| height | **float** | výška rámce tvaru, v bodech. |

### Return Value

Nově vytvořený [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metoda

Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, případně jej inicializuje výchozím stylem šablony.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se má vložit automatický tvar. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatického tvaru, který se má vložit. |
| x | **float** | x-souřadnice rámce tvaru, v bodech. |
| y | **float** | y-souřadnice rámce tvaru, v bodech. |
| width | **float** | šířka rámce tvaru, v bodech. |
| height | **float** | výška rámce tvaru, v bodech. |
| createFromTemplate | **bool** | True, pokud se má použít výchozí styl šablony (včetně neprázdného názvu, jednoduchého stylu a centrovaného textu); false, pokud se má tvar vytvořit se všemi vlastnostmi nastavenými na výchozí hodnoty. |

### Return Value

Nově vytvořený [IAutoShape](../../iautoshape/).

## Viz také

* Výčtový typ [ShapeType](../../shapetype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)