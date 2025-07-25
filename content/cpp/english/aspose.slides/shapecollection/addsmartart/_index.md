---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API Reference
description: Creates a SmartArt diagram and adds it to the end of the shape collection.
type: docs
weight: 79
url: /aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method


Creates a [SmartArt](../../../aspose.slides.smartart/) diagram and adds it to the end of the shape collection.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the diagram\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the diagram\\u2019s frame, in points. |
| width | **float** | The width of the diagram\\u2019s frame, in points. |
| height | **float** | The height of the diagram\\u2019s frame, in points. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | The [SmartArt](../../../aspose.slides.smartart/) layout type. |

### Return Value

The newly created [ISmartArt](../).
## Remarks



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## See Also

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)