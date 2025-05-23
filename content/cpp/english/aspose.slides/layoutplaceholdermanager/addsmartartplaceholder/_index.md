---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new placeholder shape to the layout slide to hold a SmartArt diagram.
type: docs
weight: 92
url: /aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) method


Adds a new placeholder shape to the layout slide to hold a [SmartArt](../../../aspose.slides.smartart/) diagram.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X coordinate of the new placeholder shape. |
| y | **float** | The Y coordinate of the new placeholder shape. |
| width | **float** | The width of the new placeholder shape. |
| height | **float** | The height of the new placeholder shape. |

### Return Value

Created [IAutoShape](../../iautoshape/) with a [SmartArt](../../../aspose.slides.smartart/) placeholder.
## Remarks



The following example shows how to add the [SmartArt](../../../aspose.slides.smartart/) placeholder shape to the layout slide. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)