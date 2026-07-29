---
title: AddSmartArt()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett SmartArt-diagram och lägger till det i slutet av figursamlingen.
type: docs
weight: 79
url: /sv/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metod

Skapar ett [SmartArt](../../../aspose.slides.smartart/) diagram och lägger till det i slutet av figursamlingen.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för diagrammets ram, i punkter. |
| y | **float** | y-koordinaten för diagrammets ram, i punkter. |
| width | **float** | bredden på diagrammets ram, i punkter. |
| height | **float** | höjden på diagrammets ram, i punkter. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Den [SmartArt](../../../aspose.slides.smartart/) layout-typen. |

### Returvärde

Den nyss skapade [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).
## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## Se även

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)