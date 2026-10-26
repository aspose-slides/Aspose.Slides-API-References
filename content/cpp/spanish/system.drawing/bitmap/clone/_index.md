---
title: Clone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia del objeto actual.
type: docs
weight: 183
url: /es/system.drawing/bitmap/clone/
---
## Bitmap::Clone() método


Crea una copia del objeto actual.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Valor devuelto

Una copia del objeto actual.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) método


Crea un objeto [Bitmap](../) que representa una copia de una región de la imagen bitmap representada por el objeto actual.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | El rectángulo que especifica la región a copiar |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | El formato de píxel para el nuevo [Bitmap](../) |

### Valor devuelto

El objeto [Bitmap](../) creado

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) método


Crea un objeto [Bitmap](../) que representa una copia de una región de la imagen bitmap representada por el objeto actual.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | El rectángulo que especifica la región a copiar |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | El formato de píxel para el nuevo [Bitmap](../) |

### Valor devuelto

El objeto [Bitmap](../) creado

## See Also

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)