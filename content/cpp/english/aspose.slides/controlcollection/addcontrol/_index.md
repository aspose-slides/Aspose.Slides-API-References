---
title: AddControl()
second_title: Aspose.Slides for C++ API Reference
description: Creates and adds a new control to the collection.
type: docs
weight: 40
url: /aspose.slides/controlcollection/addcontrol/
---
## ControlCollection::AddControl(ControlType, float, float, float, float) method


Creates and adds a new control to the collection.

```cpp
System::SharedPtr<IControl> Aspose::Slides::ControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | Type of a control to add. |
| x | **float** | The X-coordinate for a left side of shape's frame. |
| y | **float** | The Y-coordinate for a top side of shape's frame. |
| width | **float** | The width of shape's frame. |
| height | **float** | The height of shape's frame. |

### Return Value

Created control.

## See Also

* Enum [ControlType](../../controltype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IControl](../../icontrol/)
* Class [ControlCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)