---
title: AddControl()
second_title: Aspose.Slides for C++ API Reference
description: Creates and adds a new control to the collection.
type: docs
weight: 53
url: /aspose.slides/icontrolcollection/addcontrol/
---
## IControlCollection::AddControl(ControlType, float, float, float, float) method


Creates and adds a new control to the collection.

```cpp
virtual System::SharedPtr<IControl> Aspose::Slides::IControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height)=0
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

Created control [IControl](../../icontrol/).

## See Also

* Enum [ControlType](../../controltype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IControl](../../icontrol/)
* Class [IControlCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)