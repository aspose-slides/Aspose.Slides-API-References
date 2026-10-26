---
title: AddGroupShape()
second_title: Aspose.Slides pro C++ API reference
description: Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. Rámec skupiny se automaticky přizpůsobí tak, aby vyhovoval všem tvarům, které jsou do něj přidány.
type: docs
weight: 352
url: /cs/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() metoda

Vytvoří novou prázdnou skupinovou tvar a přidá ji na konec kolekce tvarů. Rámec skupiny se automaticky přizpůsobí tak, aby vyhovoval všem tvarům, které jsou do něj přidány.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### Návratová hodnota

Nově vytvořený [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metoda

Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary a přidá vzniklou skupinu na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) obsahující vektorový obsah k převodu na tvary. |
| x | **float** | x-souřadnice rámce skupiny, v bodech. |
| y | **float** | y-souřadnice rámce skupiny, v bodech. |
| width | **float** | Šířka rámce skupiny, v bodech. |
| height | **float** | Výška rámce skupiny, v bodech. |

### Návratová hodnota

Nově vytvořený [IGroupShape](../../igroupshape/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IGroupShape](../../igroupshape/)
* Třída [IShapeCollection](../)
* Třída [ISvgImage](../../isvgimage/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)