---
title: AddSmartArt()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza a SmartArt diagramot, és hozzáadja az alakzatgyűjtemény végéhez.
type: docs
weight: 40
url: /hu/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metódus

Létrehozza a [SmartArt](../../../aspose.slides.smartart/) diagramot, és hozzáadja a alakzatgyűjtemény végéhez.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | A diagram keretének x-koordinátája pontban. |
| y | **float** | A diagram keretének y-koordinátája pontban. |
| width | **float** | A diagram keretének szélessége pontban. |
| height | **float** | A diagram keretének magassága pontban. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | A [SmartArt](../../../aspose.slides.smartart/) elrendezéstípus. |

### Visszatérési érték

Az újonnan létrehozott [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).
## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Lásd még

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)