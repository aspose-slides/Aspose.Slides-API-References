---
title: BeginContainer()
second_title: Aspose.Slides C++ API referencia
description: Elment egy tárolót a jelenlegi objektum állapotával, megnyit és használ egy új tárolót, majd visszaadja a mentett tárolót.
type: docs
weight: 976
url: /hu/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() metódus


Elment egy tárolót a jelenlegi objektum állapotával, megnyit és használ egy új tárolót, majd visszaadja a mentett tárolót.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) metódus


Elment egy tárolót a jelenlegi objektum állapotával, megnyit és használ egy új tárolót, majd visszaadja a mentett tárolót.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Az új tároló méretezési transzformációját meghatározó téglalap. **srcrect**-del együtt használva |
| srcrect | [Rectangle](../../rectangle/) | Az új tároló méretezési transzformációját meghatározó téglalap. **dstrect**-del együtt használva |
| unit | [GraphicsUnit](../../graphicsunit/) | Az új tároló mértékegységét meghatározó érték |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) metódus


Elment egy tárolót a jelenlegi objektum állapotával, megnyit és használ egy új tárolót, majd visszaadja a mentett tárolót.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Az új tároló méretezési transzformációját meghatározó téglalap. **srcrect**-del együtt használva |
| srcrect | [RectangleF](../../rectanglef/) | Az új tároló méretezési transzformációját meghatározó téglalap. **dstrect**-del együtt használva |
| unit | [GraphicsUnit](../../graphicsunit/) | Az új tároló mértékegységét meghatározó érték |

## Lásd még

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)