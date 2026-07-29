---
title: AddSmartArt()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen.
type: docs
weight: 40
url: /sv/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metod

Skapar ett [SmartArt](../../../aspose.slides.smartart/) diagram och lägger till det i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | Diagrammets ramens x-koordinat i punkter. |
| y | **float** | Diagrammets ramens y-koordinat i punkter. |
| width | **float** | Diagrammets ramens bredd i punkter. |
| height | **float** | Diagrammets ramens höjd i punkter. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Den [SmartArt](../../../aspose.slides.smartart/) layouttypen. |

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
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)