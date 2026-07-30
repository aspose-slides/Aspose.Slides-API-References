---
title: AddSmartArt()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů.
type: docs
weight: 79
url: /cs/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metoda

Vytvoří [SmartArt](../../../aspose.slides.smartart/) diagram a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice rámce diagramu v bodech. |
| y | **float** | Y-souřadnice rámce diagramu v bodech. |
| width | **float** | Šířka rámce diagramu v bodech. |
| height | **float** | Výška rámce diagramu v bodech. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Typ rozvržení [SmartArt](../../../aspose.slides.smartart/). |

### Návratová hodnota

Nově vytvořený [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Viz také

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)