---
title: BeginContainer()
second_title: Aspose.Slides för C++ API-referens
description: Sparar en behållare med det aktuella tillståndet för detta objekt, öppnar och använder en ny behållare och returnerar den sparade behållaren.
type: docs
weight: 976
url: /sv/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() metod

Sparar en behållare med det aktuella tillståndet för detta objekt, öppnar och använder en ny behållare och returnerar den sparade behållaren.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) metod

Sparar en behållare med det aktuella tillståndet för detta objekt, öppnar och använder en ny behållare och returnerar den sparade behållaren.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Rektangeln som specificerar en skaltransformation av den nya behållaren. Används tillsammans med **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | Rektangeln som specificerar en skaltransformation av den nya behållaren. Används tillsammans med **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Värdet som specificerar måttenheten för den nya behållaren |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) metod

Sparar en behållare med det aktuella tillståndet för detta objekt, öppnar och använder en ny behållare och returnerar den sparade behållaren.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Rektangeln som specificerar en skaltransformation av den nya behållaren. Används tillsammans med **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | Rektangeln som specificerar en skaltransformation av den nya behållaren. Används tillsammans med **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Värdet som specificerar måttenheten för den nya behållaren |

## Se även

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Klass [Graphics](../)
* Klass [Rectangle](../../rectangle/)
* Klass [RectangleF](../../rectanglef/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)