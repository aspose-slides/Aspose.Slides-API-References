---
title: BeginContainer()
second_title: Aspose.Slides for C++ API Reference
description: Saves a container with the current state of this object, opens and uses a new container and returns the saved container.
type: docs
weight: 976
url: /system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() method


Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) method


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

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) method


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

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)