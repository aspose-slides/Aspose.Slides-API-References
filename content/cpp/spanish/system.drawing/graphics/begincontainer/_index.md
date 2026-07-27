---
title: BeginContainer()
second_title: Referencia de API de Aspose.Slides para C++
description: Guarda un contenedor con el estado actual de este objeto, abre y usa un nuevo contenedor y devuelve el contenedor guardado.
type: docs
weight: 976
url: /es/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() método

Guarda un contenedor con el estado actual de este objeto, abre y usa un nuevo contenedor y devuelve el contenedor guardado.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) método

Guarda un contenedor con el estado actual de este objeto, abre y usa un nuevo contenedor y devuelve el contenedor guardado.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | El rectángulo que especifica una transformación de escala del nuevo contenedor. Se usa junto con **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | El rectángulo que especifica una transformación de escala del nuevo contenedor. Se usa junto con **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | El valor que especifica la unidad de medida del nuevo contenedor |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) método

Guarda un contenedor con el estado actual de este objeto, abre y usa un nuevo contenedor y devuelve el contenedor guardado.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | El rectángulo que especifica una transformación de escala del nuevo contenedor. Se usa junto con **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | El rectángulo que especifica una transformación de escala del nuevo contenedor. Se usa junto con **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | El valor que especifica la unidad de medida del nuevo contenedor |

## Ver también

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Clase [Graphics](../)
* Clase [Rectangle](../../rectangle/)
* Clase [RectangleF](../../rectanglef/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)