---
title: BeginContainer()
second_title: Aspose.Slides for C++ API Reference
description: Saves a container with the current state of this object, opens and uses a new container and returns the saved container.
type: docs
weight: 976
url: /cpp/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() method


Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Graphics::BeginContainer([Rectangle](../../rectangle/), [Rectangle](../../rectangle/), [GraphicsUnit](../../graphicsunit/)) method


Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | The rectangle that specifies a scale transformation of the new container. Used together with **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | The rectangle that specifies a scale transformation of the new container. Used together with **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | The value that specifies the unit of measure of the new container |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Rectangle](../../rectangle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Graphics::BeginContainer([RectangleF](../../rectanglef/), [RectangleF](../../rectanglef/), [GraphicsUnit](../../graphicsunit/)) method


Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | The rectangle that specifies a scale transformation of the new container. Used together with **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | The rectangle that specifies a scale transformation of the new container. Used together with **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | The value that specifies the unit of measure of the new container |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [RectangleF](../../rectanglef/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
