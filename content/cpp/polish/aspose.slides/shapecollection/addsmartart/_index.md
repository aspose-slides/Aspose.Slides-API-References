---
title: AddSmartArt()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów.
type: docs
weight: 79
url: /pl/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metoda

Tworzy diagram [SmartArt](../../../aspose.slides.smartart/) i dodaje go na koniec kolekcji kształtów.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x ramki diagramu, w punktach. |
| y | **float** | Współrzędna y ramki diagramu, w punktach. |
| width | **float** | Szerokość ramki diagramu, w punktach. |
| height | **float** | Wysokość ramki diagramu, w punktach. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Typ układu [SmartArt](../../../aspose.slides.smartart/). |

### Wartość zwracana

Nowo utworzony [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Zobacz także

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)