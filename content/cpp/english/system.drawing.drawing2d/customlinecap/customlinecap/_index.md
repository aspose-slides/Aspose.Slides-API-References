---
title: CustomLineCap()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of CustomLineCap class that represents a user-defined line cap with the specified properties.
type: docs
weight: 1
url: /system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) constructor


Constructs a new instance of [CustomLineCap](../) class that represents a user-defined line cap with the specified properties.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Specifies a fill for the custom cap |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Specifies an outline of the custom cap |
| baseCap | [LineCap](../../linecap/) | The base line cap from which the custom cap is created |
| baseInset | **float** | Specifies the distance between the line and the cap |

## See Also

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)