---
title: AddSmartArt()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy SmartArt diagramot, és hozzáadja az alakzatgyűjtemény végéhez.
type: docs
weight: 79
url: /hu/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method

Létrehoz egy [SmartArt](../../../aspose.slides.smartart/) diagramot, és hozzáadja a alakzatgyűjtemény végéhez.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A diagram keretének x-koordinátája pontban. |
| y | **float** | A diagram keretének y-koordinátája pontban. |
| width | **float** | A diagram keretének szélessége pontban. |
| height | **float** | A diagram keretének magassága pontban. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) elrendezés típusa. |

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
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)