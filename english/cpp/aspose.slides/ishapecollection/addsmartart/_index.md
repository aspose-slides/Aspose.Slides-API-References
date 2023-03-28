---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API Reference
description: Add SmartArt diagram.
type: docs
weight: 40
url: /cpp/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(**float**, **float**, **float**, **float**, [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)) method


Add [SmartArt](../../../aspose.slides.smartart/) diagram.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X-coordinate for a left side of diagram's frame. |
| y | **float** | The Y-coordinate for a left side of diagram's frame. |
| width | **float** | The width of diagram's frame. |
| height | **float** | The height of diagram's frame. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | The type of [SmartArt](../../../aspose.slides.smartart/) diagram |

### Return Value

Create [SmartArt](../../../aspose.slides.smartart/) diagram
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
