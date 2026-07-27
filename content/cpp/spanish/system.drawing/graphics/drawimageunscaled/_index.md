---
title: DrawImageUnscaled()
second_title: Referencia de la API de Aspose.Slides para C++
description: Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada.
type: docs
weight: 443
url: /es/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) método


Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| x | int | La coordenada X de la esquina superior izquierda de la imagen dibujada |
| y | int | La coordenada Y de la esquina superior izquierda de la imagen dibujada |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) método


Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| x | int | La coordenada X de la esquina superior izquierda de la imagen dibujada |
| y | int | La coordenada Y de la esquina superior izquierda de la imagen dibujada |
| width | int | No usado |
| height | int | No usado |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) método


Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| rect | const [Rectangle](../../rectangle/)\& | El Rectangle que especifica la esquina superior izquierda de la imagen dibujada. Las propiedades X e Y del Rectangle especifican la esquina superior izquierda. Los valores de ancho y alto se ignoran. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) método


Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| point | const [Point](../../point/)\& | La estructura [Point](../../point/) que especifica la esquina superior izquierda de la imagen dibujada. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Image](../../image/)
* Clase [Graphics](../)
* Clase [Rectangle](../../rectangle/)
* Clase [Point](../../point/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)