---
title: DrawImage()
second_title: Referencia de API de Aspose.Slides para C++
description: NO IMPLEMENTADO.
type: docs
weight: 430
url: /es/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) método


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORADO |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORADO |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Dibuja la región especificada de la imagen indicada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Una matriz que contiene tres puntos que definen un paralelogramo en la superficie de dibujo donde se dibujará la imagen |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rectángulo que define la región de la imagen especificada que se dibujará |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida usadas por el parámetro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica la información de color y gamma para la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Dibuja la región especificada de la imagen indicada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Una vista de matriz que contiene tres puntos que definen un paralelogramo en la superficie de dibujo donde se dibujará la imagen |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rectángulo que define la región de la imagen especificada que se dibujará |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida usadas por el parámetro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica la información de color y gamma para la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Dibuja la región especificada de la imagen indicada en la ubicación especificada.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Una pila de matriz que contiene tres puntos que definen un paralelogramo en la superficie de dibujo donde se dibujará la imagen |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rectángulo que define la región de la imagen especificada que se dibujará |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida usadas por el parámetro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica la información de color y gamma para la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) método


Dibuja la imagen especificada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| x | int | La coordenada X de la esquina superior izquierda de la imagen dibujada |
| y | int | La coordenada Y de la esquina superior izquierda de la imagen dibujada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) método


Dibuja la imagen especificada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| x | **float** | La coordenada X de la esquina superior izquierda de la imagen dibujada |
| y | **float** | La coordenada Y de la esquina superior izquierda de la imagen dibujada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) método


Dibuja la imagen especificada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| pt | [Point](../../point/) | La ubicación de la esquina superior izquierda de la imagen dibujada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) método


Dibuja la imagen especificada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| pt | [PointF](../../pointf/) | La ubicación de la esquina superior izquierda de la imagen dibujada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) método


Dibuja la imagen especificada en el rectángulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| x | int | La coordenada X de la esquina superior izquierda del rectángulo donde se dibujará la imagen |
| y | int | La coordenada Y de la esquina superior izquierda del rectángulo donde se dibujará la imagen |
| width | int | El ancho del rectángulo donde se dibujará la imagen |
| height | int | La altura del rectángulo donde se dibujará la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) método


Dibuja la imagen especificada en el rectángulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| x | **float** | La coordenada X de la esquina superior izquierda del rectángulo donde se dibujará la imagen |
| y | **float** | La coordenada Y de la esquina superior izquierda del rectángulo donde se dibujará la imagen |
| width | **float** | El ancho del rectángulo donde se dibujará la imagen |
| height | **float** | La altura del rectángulo donde se dibujará la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) método


Dibuja la región especificada de la imagen indicada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destRect | [RectangleF](../../rectanglef/) | Un rectángulo donde se dibujará la imagen |
| srcRect | [RectangleF](../../rectanglef/) | Un rectángulo que define la región de la imagen especificada que se dibujará |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida usadas por el parámetro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) método


Dibuja la región especificada de la imagen indicada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destRect | [Rectangle](../../rectangle/) | Un rectángulo donde se dibujará la imagen |
| srcRect | [Rectangle](../../rectangle/) | Un rectángulo que define la región de la imagen especificada que se dibujará |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida usadas por el parámetro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) método


Dibuja la región especificada de la imagen indicada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| x | int | La coordenada X de la esquina superior izquierda del rectángulo donde se dibujará la imagen |
| y | int | La coordenada Y de la esquina superior izquierda del rectángulo donde se dibujará la imagen |
| srcRect | [Rectangle](../../rectangle/) | Un rectángulo que define la región de la imagen especificada que se dibujará |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida usadas por el parámetro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) método


Dibuja la imagen especificada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| rect | const [Rectangle](../../rectangle/)\& | Un rectángulo donde se dibujará la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) método


Dibuja la imagen especificada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectángulo donde se dibujará la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Dibuja la región especificada de la imagen indicada en el rectángulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destRect | [Rectangle](../../rectangle/) | Un rectángulo donde se dibujará la imagen |
| srcX | int | La coordenada X de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcY | int | La coordenada Y de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcWidth | int | El ancho de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcHeight | int | La altura de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida en las que se especifican los parámetros **srcX**, **srcY**, **srcWidth** y **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica la información de color y gamma para la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Dibuja la región especificada de la imagen indicada en el rectángulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destRect | [Rectangle](../../rectangle/) | Un rectángulo donde se dibujará la imagen |
| srcX | **float** | La coordenada X de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcY | **float** | La coordenada Y de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcWidth | **float** | El ancho de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcHeight | **float** | La altura de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida en las que se especifican los parámetros **srcX**, **srcY**, **srcWidth** y **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica la información de color y gamma para la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) método


Dibuja la región especificada de la imagen indicada en el rectángulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destRect | [Rectangle](../../rectangle/) | Un rectángulo donde se dibujará la imagen |
| srcX | int | La coordenada X de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcY | int | La coordenada Y de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcWidth | int | El ancho de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcHeight | int | La altura de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida en las que se especifican los parámetros **srcX**, **srcY**, **srcWidth** y **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) método


Dibuja la región especificada de la imagen indicada en el rectángulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destRect | [Rectangle](../../rectangle/) | Un rectángulo donde se dibujará la imagen |
| srcX | **float** | La coordenada X de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcY | **float** | La coordenada Y de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcWidth | **float** | El ancho de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcHeight | **float** | La altura de la esquina superior izquierda del rectángulo que especifica la porción de la imagen a dibujar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida en las que se especifican los parámetros **srcX**, **srcY**, **srcWidth** y **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) método


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) método


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) método


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) método


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) método


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) método


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) método


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) método


Dibuja la región especificada de la imagen indicada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Una matriz que contiene tres puntos que definen un paralelogramo en la superficie de dibujo donde se dibujará la imagen |
| srcRect | [Rectangle](../../rectangle/) | Un rectángulo que define la región de la imagen especificada que se dibujará |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida usadas por el parámetro **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Especifica la información de color y gamma para la imagen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) método


Dibuja la región especificada de la imagen indicada en la ubicación especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen a dibujar |
| x | **float** | La coordenada X de la esquina superior izquierda del rectángulo donde se dibujará la imagen |
| y | **float** | La coordenada Y de la esquina superior izquierda del rectángulo donde se dibujará la imagen |
| srcRect | [RectangleF](../../rectanglef/) | Un rectángulo que define la región de la imagen especificada que se dibujará |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Las unidades de medida usadas por el parámetro **srcRect** |

## Ver también

* Enumeración [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Clase [Image](../../image/)
* Clase [Point](../../point/)
* Clase [Graphics](../)
* Clase [PointF](../../pointf/)
* Clase [RectangleF](../../rectanglef/)
* Clase [Rectangle](../../rectangle/)
* Clase [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)