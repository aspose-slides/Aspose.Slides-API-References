---
title: DrawImage()
second_title: Riferimento API di Aspose.Slides per C++
description: NON IMPLEMENTATO.
type: docs
weight: 430
url: /it/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) method

NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORED |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORED |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

Disegna la regione specificata dell'immagine indicata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Un array contenente tre punti che definiscono un parallelogramma sulla superficie di disegno su cui disegnare l'immagine |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rettangolo che definisce la regione dell'immagine specificata da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura utilizzate dal parametro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifica le informazioni di colore e gamma per l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

Disegna la regione specificata dell'immagine indicata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Una vista di array contenente tre punti che definiscono un parallelogramma sulla superficie di disegno su cui disegnare l'immagine |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rettangolo che definisce la regione dell'immagine specificata da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura utilizzate dal parametro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifica le informazioni di colore e gamma per l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

Disegna la regione specificata dell'immagine indicata nella posizione specificata.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Un array stack contenente tre punti che definiscono un parallelogramma sulla superficie di disegno su cui disegnare l'immagine |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rettangolo che definisce la regione dell'immagine specificata da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura utilizzate dal parametro **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifica le informazioni di colore e gamma per l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) method

Disegna l'immagine specificata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| x | int | La coordinata X dell'angolo superiore sinistro dell'immagine disegnata |
| y | int | La coordinata Y dell'angolo superiore sinistro dell'immagine disegnata |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) method

Disegna l'immagine specificata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| x | **float** | La coordinata X dell'angolo superiore sinistro dell'immagine disegnata |
| y | **float** | La coordinata Y dell'angolo superiore sinistro dell'immagine disegnata |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) method

Disegna l'immagine specificata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| pt | [Point](../../point/) | La posizione dell'angolo superiore sinistro dell'immagine disegnata |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) method

Disegna l'immagine specificata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| pt | [PointF](../../pointf/) | La posizione dell'angolo superiore sinistro dell'immagine disegnata |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) method

Disegna l'immagine specificata nel rettangolo specificato.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| x | int | La coordinata X dell'angolo superiore sinistro del rettangolo su cui disegnare l'immagine |
| y | int | La coordinata Y dell'angolo superiore sinistro del rettangolo su cui disegnare l'immagine |
| width | int | La larghezza del rettangolo su cui disegnare l'immagine |
| height | int | L'altezza del rettangolo su cui disegnare l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) method

Disegna l'immagine specificata nel rettangolo specificato.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| x | **float** | La coordinata X dell'angolo superiore sinistro del rettangolo su cui disegnare l'immagine |
| y | **float** | La coordinata Y dell'angolo superiore sinistro del rettangolo su cui disegnare l'immagine |
| width | **float** | La larghezza del rettangolo su cui disegnare l'immagine |
| height | **float** | L'altezza del rettangolo su cui disegnare l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) method

Disegna la regione specificata dell'immagine indicata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destRect | [RectangleF](../../rectanglef/) | Un rettangolo su cui disegnare l'immagine |
| srcRect | [RectangleF](../../rectanglef/) | Un rettangolo che definisce la regione dell'immagine specificata da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura utilizzate dal parametro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) method

Disegna la regione specificata dell'immagine indicata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destRect | [Rectangle](../../rectangle/) | Un rettangolo su cui disegnare l'immagine |
| srcRect | [Rectangle](../../rectangle/) | Un rettangolo che definisce la regione dell'immagine specificata da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura utilizzate dal parametro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) method

Disegna la regione specificata dell'immagine indicata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| x | int | La coordinata X dell'angolo superiore sinistro del rettangolo su cui disegnare l'immagine |
| y | int | La coordinata Y dell'angolo superiore sinistro del rettangolo su cui disegnare l'immagine |
| srcRect | [Rectangle](../../rectangle/) | Un rettangolo che definisce la regione dell'immagine specificata da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura utilizzate dal parametro **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) method

Disegna l'immagine specificata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| rect | const [Rectangle](../../rectangle/)\& | Un rettangolo su cui disegnare l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) method

Disegna l'immagine specificata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| rect | const [RectangleF](../../rectanglef/)\& | Un rettangolo su cui disegnare l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

Disegna la regione specificata dell'immagine nel rettangolo specificato.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destRect | [Rectangle](../../rectangle/) | Un rettangolo su cui disegnare l'immagine |
| srcX | int | La coordinata X dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcY | int | La coordinata Y dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcWidth | int | La larghezza dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcHeight | int | L'altezza dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura in cui sono specificati i parametri **srcX**, **srcY**, **srcWidth** e **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifica le informazioni di colore e gamma per l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

Disegna la regione specificata dell'immagine nel rettangolo specificato.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destRect | [Rectangle](../../rectangle/) | Un rettangolo su cui disegnare l'immagine |
| srcX | **float** | La coordinata X dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcY | **float** | La coordinata Y dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcWidth | **float** | La larghezza del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcHeight | **float** | L'altezza del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura in cui sono specificati i parametri **srcX**, **srcY**, **srcWidth** e **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifica le informazioni di colore e gamma per l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) method

Disegna la regione specificata dell'immagine nel rettangolo specificato.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destRect | [Rectangle](../../rectangle/) | Un rettangolo su cui disegnare l'immagine |
| srcX | int | La coordinata X dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcY | int | La coordinata Y dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcWidth | int | La larghezza del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcHeight | int | L'altezza del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura in cui sono specificati i parametri **srcX**, **srcY**, **srcWidth** e **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) method

Disegna la regione specificata dell'immagine nel rettangolo specificato.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destRect | [Rectangle](../../rectangle/) | Un rettangolo su cui disegnare l'immagine |
| srcX | **float** | La coordinata X dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcY | **float** | La coordinata Y dell'angolo superiore sinistro del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcWidth | **float** | La larghezza del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcHeight | **float** | L'altezza del rettangolo che specifica la porzione dell'immagine da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura in cui sono specificati i parametri **srcX**, **srcY**, **srcWidth** e **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) method

NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) method

NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) method

NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) method

NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) method

NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) method

NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) method

NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) method

Disegna la regione specificata dell'immagine indicata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Un array contenente tre punti che definiscono un parallelogramma sulla superficie di disegno su cui disegnare l'immagine |
| srcRect | [Rectangle](../../rectangle/) | Un rettangolo che definisce la regione dell'immagine specificata da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura utilizzate dal parametro **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Specifica le informazioni di colore e gamma per l'immagine |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) method

Disegna la regione specificata dell'immagine indicata nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| x | **float** | La coordinata X dell'angolo superiore sinistro del rettangolo su cui disegnare l'immagine |
| y | **float** | La coordinata Y dell'angolo superiore sinistro del rettangolo su cui disegnare l'immagine |
| srcRect | [RectangleF](../../rectanglef/) | Un rettangolo che definisce la regione dell'immagine specificata da disegnare |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura utilizzate dal parametro **srcRect** |

## Vedi anche

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Classe [Image](../../image/)
* Classe [Point](../../point/)
* Classe [Graphics](../)
* Classe [PointF](../../pointf/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Rectangle](../../rectangle/)
* Classe [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)