---
title: BeginContainer()
second_title: Aspose.Slides voor C++ API Referentie
description: Slaat een container op met de huidige staat van dit object, opent en gebruikt een nieuwe container en retourneert de opgeslagen container.
type: docs
weight: 976
url: /nl/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() methode


Slaat een container op met de huidige staat van dit object, opent en gebruikt een nieuwe container en retourneert de opgeslagen container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) methode


Slaat een container op met de huidige staat van dit object, opent en gebruikt een nieuwe container en retourneert de opgeslagen container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | De rechthoek die een schaaltransformatie van de nieuwe container specificeert. Wordt samen gebruikt met **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | De rechthoek die een schaaltransformatie van de nieuwe container specificeert. Wordt samen gebruikt met **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | De waarde die de meeteenheid van de nieuwe container specificeert |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) methode


Slaat een container op met de huidige staat van dit object, opent en gebruikt een nieuwe container en retourneert de opgeslagen container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | De rechthoek die een schaaltransformatie van de nieuwe container specificeert. Wordt samen gebruikt met **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | De rechthoek die een schaaltransformatie van de nieuwe container specificeert. Wordt samen gebruikt met **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | De waarde die de meeteenheid van de nieuwe container specificeert |

## Zie ook

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)