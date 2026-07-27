---
title: DrawImage()
second_title: Referência da API Aspose.Slides para C++
description: NÃO IMPLEMENTADO.
type: docs
weight: 430
url: /pt/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) método


NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORADO |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORADO |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Desenha a região especificada da imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Um array contendo três pontos que definem um paralelogramo na superfície de desenho onde a imagem será desenhada |
| srcRect | const [RectangleF](../../rectanglef/)\& | Um retângulo que define a região da imagem especificada a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida usadas pelo parâmetro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica informações de coloração e gama para a imagem |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Desenha a região especificada da imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Um array view contendo três pontos que definem um paralelogramo na superfície de desenho onde a imagem será desenhada |
| srcRect | const [RectangleF](../../rectanglef/)\& | Um retângulo que define a região da imagem especificada a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida usadas pelo parâmetro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica informações de coloração e gama para a imagem |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Desenha a região especificada da imagem especificada na localização especificada.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Um stack array contendo três pontos que definem um paralelogramo na superfície de desenho onde a imagem será desenhada |
| srcRect | const [RectangleF](../../rectanglef/)\& | Um retângulo que define a região da imagem especificada a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida usadas pelo parâmetro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica informações de coloração e gama para a imagem |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) método


Desenha a imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| x | int | A coordenada X do canto superior esquerdo da imagem desenhada |
| y | int | A coordenada Y do canto superior esquerdo da imagem desenhada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) método


Desenha a imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| x | **float** | A coordenada X do canto superior esquerdo da imagem desenhada |
| y | **float** | A coordenada Y do canto superior esquerdo da imagem desenhada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) método


Desenha a imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| pt | [Point](../../point/) | A localização do canto superior esquerdo da imagem desenhada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) método


Desenha a imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| pt | [PointF](../../pointf/) | A localização do canto superior esquerdo da imagem desenhada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) método


Desenha a imagem especificada no retângulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| x | int | A coordenada X do canto superior esquerdo do retângulo onde a imagem será desenhada |
| y | int | A coordenada Y do canto superior esquerdo do retângulo onde a imagem será desenhada |
| width | int | A largura do retângulo onde a imagem será desenhada |
| height | int | A altura do retângulo onde a imagem será desenhada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) método


Desenha a imagem especificada no retângulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| x | **float** | A coordenada X do canto superior esquerdo do retângulo onde a imagem será desenhada |
| y | **float** | A coordenada Y do canto superior esquerdo do retângulo onde a imagem será desenhada |
| width | **float** | A largura do retângulo onde a imagem será desenhada |
| height | **float** | A altura do retângulo onde a imagem será desenhada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) método


Desenha a região especificada da imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destRect | [RectangleF](../../rectanglef/) | Um retângulo onde a imagem será desenhada |
| srcRect | [RectangleF](../../rectanglef/) | Um retângulo que define a região da imagem especificada a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida usadas pelo parâmetro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) método


Desenha a região especificada da imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destRect | [Rectangle](../../rectangle/) | Um retângulo onde a imagem será desenhada |
| srcRect | [Rectangle](../../rectangle/) | Um retângulo que define a região da imagem especificada a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida usadas pelo parâmetro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) método


Desenha a região especificada da imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| x | int | A coordenada X do canto superior esquerdo do retângulo onde a imagem será desenhada |
| y | int | A coordenada Y do canto superior esquerdo do retângulo onde a imagem será desenhada |
| srcRect | [Rectangle](../../rectangle/) | Um retângulo que define a região da imagem especificada a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida usadas pelo parâmetro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) método


Desenha a imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| rect | const [Rectangle](../../rectangle/)\& | Um retângulo onde a imagem será desenhada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) método


Desenha a imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| rect | const [RectangleF](../../rectanglef/)\& | Um retângulo onde a imagem será desenhada |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Desenha a região especificada da imagem especificada no retângulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destRect | [Rectangle](../../rectangle/) | Um retângulo onde a imagem será desenhada |
| srcX | int | A coordenada X do canto superior esquerdo do retângulo que especifica a porção da imagem a ser desenhada |
| srcY | int | A coordenada Y do canto superior esquerdo do retângulo que especifica a porção da imagem a ser desenhada |
| srcWidth | int | A largura do retângulo que especifica a porção da imagem a ser desenhada |
| srcHeight | int | A altura do retângulo que especifica a porção da imagem a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida nas quais os parâmetros **srcX**, **srcY**, **srcWidth** e **srcHeight** são especificados |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica informações de coloração e gama para a imagem |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) método


Desenha a região especificada da imagem especificada no retângulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destRect | [Rectangle](../../rectangle/) | Um retângulo onde a imagem será desenhada |
| srcX | **float** | A coordenada X do canto superior esquerdo do retângulo que especifica a porção da imagem a ser desenhada |
| srcY | **float** | A coordenada Y do canto superior esquerdo do retângulo que especifica a porção da imagem a ser desenhada |
| srcWidth | **float** | A largura do retângulo que especifica a porção da imagem a ser desenhada |
| srcHeight | **float** | A altura do retângulo que especifica a porção da imagem a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida nas quais os parâmetros **srcX**, **srcY**, **srcWidth** e **srcHeight** são especificados |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Especifica informações de coloração e gama para a imagem |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) método


Desenha a região especificada da imagem especificada no retângulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destRect | [Rectangle](../../rectangle/) | Um retângulo onde a imagem será desenhada |
| srcX | int | A coordenada X do canto superior esquerdo do retângulo que especifica a porção da imagem a ser desenhada |
| srcY | int | A coordenada Y do canto superior esquerdo do retângulo que especifica a porção da imagem a ser desenhada |
| srcWidth | int | A largura do retângulo que especifica a porção da imagem a ser desenhada |
| srcHeight | int | A altura do retângulo que especifica a porção da imagem a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida nas quais os parâmetros **srcX**, **srcY**, **srcWidth** e **srcHeight** são especificados |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) método


Desenha a região especificada da imagem especificada no retângulo especificado.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destRect | [Rectangle](../../rectangle/) | Um retângulo onde a imagem será desenhada |
| srcX | **float** | A coordenada X do canto superior esquerdo do retângulo que especifica a porção da imagem a ser desenhada |
| srcY | **float** | A coordenada Y do canto superior esquerdo do retângulo que especifica a porção da imagem a ser desenhada |
| srcWidth | **float** | A largura do retângulo que especifica a porção da imagem a ser desenhada |
| srcHeight | **float** | A altura do retângulo que especifica a porção da imagem a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida nas quais os parâmetros **srcX**, **srcY**, **srcWidth** e **srcHeight** são especificados |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) método


NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) método


NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) método


NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) método


NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) método


NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) método


NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) método


NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) método


Desenha a região especificada da imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Um array contendo três pontos que definem um paralelogramo na superfície de desenho onde a imagem será desenhada |
| srcRect | [Rectangle](../../rectangle/) | Um retângulo que define a região da imagem especificada a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida usadas pelo parâmetro **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Especifica informações de coloração e gama para a imagem |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) método


Desenha a região especificada da imagem especificada na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| x | **float** | A coordenada X do canto superior esquerdo do retângulo onde a imagem será desenhada |
| y | **float** | A coordenada Y do canto superior esquerdo do retângulo onde a imagem será desenhada |
| srcRect | [RectangleF](../../rectanglef/) | Um retângulo que define a região da imagem especificada a ser desenhada |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida usadas pelo parâmetro **srcRect** |

## See Also

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Class [Image](../../image/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)