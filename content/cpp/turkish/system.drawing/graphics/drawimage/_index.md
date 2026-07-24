---
title: DrawImage()
second_title: Aspose.Slides for C++ API Referansı
description: UYGULANMADI.
type: docs
weight: 430
url: /tr/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | GÖZARDI |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | GÖZARDI |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen konumda çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Görüntünün çizileceği çizim yüzeyinde bir paralelkenar tanımlayan üç nokta içeren bir dizi |
| srcRect | const [RectangleF](../../rectanglef/)\& | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Görüntü için renkleme ve gama bilgilerini belirtir |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen konumda çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Çizim yüzeyinde bir paralelkenar tanımlayan üç nokta içeren bir dizi görünümü |
| srcRect | const [RectangleF](../../rectanglef/)\& | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Görüntü için renkleme ve gama bilgilerini belirtir |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen konumda çizer.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Çizim yüzeyinde bir paralelkenar tanımlayan üç nokta içeren bir yığın dizisi |
| srcRect | const [RectangleF](../../rectanglef/)\& | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Görüntü için renkleme ve gama bilgilerini belirtir |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) metot

Belirtilen konumda belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| x | int | Çizilen görüntünün sol üst köşesinin X koordinatı |
| y | int | Çizilen görüntünün sol üst köşesinin Y koordinatı |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) metot

Belirtilen konumda belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| x | **float** | Çizilen görüntünün sol üst köşesinin X koordinatı |
| y | **float** | Çizilen görüntünün sol üst köşesinin Y koordinatı |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) metot

Belirtilen konumda belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| pt | [Point](../../point/) | Çizilen görüntünün sol üst köşesinin konumu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) metot

Belirtilen konumda belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| pt | [PointF](../../pointf/) | Çizilen görüntünün sol üst köşesinin konumu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) metot

Belirtilen görüntüyü belirtilen dikdörtgene çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| x | int | Görüntünün çizileceği dikdörtgenin sol üst köşesinin X koordinatı |
| y | int | Görüntünün çizileceği dikdörtgenin sol üst köşesinin Y koordinatı |
| width | int | Görüntünün çizileceği dikdörtgenin genişliği |
| height | int | Görüntünün çizileceği dikdörtgenin yüksekliği |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) metot

Belirtilen görüntüyü belirtilen dikdörtgene çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| x | **float** | Görüntünün çizileceği dikdörtgenin sol üst köşesinin X koordinatı |
| y | **float** | Görüntünün çizileceği dikdörtgenin sol üst köşesinin Y koordinatı |
| width | **float** | Görüntünün çizileceği dikdörtgenin genişliği |
| height | **float** | Görüntünün çizileceği dikdörtgenin yüksekliği |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen konumda çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destRect | [RectangleF](../../rectanglef/) | Görüntünün çizileceği dikdörtgen |
| srcRect | [RectangleF](../../rectanglef/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen konumda çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destRect | [Rectangle](../../rectangle/) | Görüntünün çizileceği dikdörtgen |
| srcRect | [Rectangle](../../rectangle/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen konumda çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| x | int | Görüntünün çizileceği dikdörtgenin sol üst köşesinin X koordinatı |
| y | int | Görüntünün çizileceği dikdörtgenin sol üst köşesinin Y koordinatı |
| srcRect | [Rectangle](../../rectangle/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) metot

Belirtilen konumda belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| rect | const [Rectangle](../../rectangle/)\& | Görüntünün çizileceği dikdörtgen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) metot

Belirtilen konumda belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| rect | const [RectangleF](../../rectanglef/)\& | Görüntünün çizileceği dikdörtgen |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen dikdörtgene çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destRect | [Rectangle](../../rectangle/) | Görüntünün çizileceği dikdörtgen |
| srcX | int | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| srcY | int | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| srcWidth | int | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin genişliği |
| srcHeight | int | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin yüksekliği |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**, **srcY**, **srcWidth** ve **srcHeight** parametrelerinin belirtildiği ölçüm birimleri |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Görüntü için renkleme ve gama bilgilerini belirtir |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen dikdörtgene çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destRect | [Rectangle](../../rectangle/) | Görüntünün çizileceği dikdörtgen |
| srcX | **float** | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| srcY | **float** | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| srcWidth | **float** | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin genişliği |
| srcHeight | **float** | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin yüksekliği |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**, **srcY**, **srcWidth** ve **srcHeight** parametrelerinin belirtildiği ölçüm birimleri |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Görüntü için renkleme ve gama bilgilerini belirtir |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen dikdörtgene çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destRect | [Rectangle](../../rectangle/) | Görüntünün çizileceği dikdörtgen |
| srcX | int | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| srcY | int | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| srcWidth | int | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin genişliği |
| srcHeight | int | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin yüksekliği |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**, **srcY**, **srcWidth** ve **srcHeight** parametrelerinin belirtildiği ölçüm birimleri |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen dikdörtgene çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destRect | [Rectangle](../../rectangle/) | Görüntünün çizileceği dikdörtgen |
| srcX | **float** | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| srcY | **float** | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| srcWidth | **float** | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin genişliği |
| srcHeight | **float** | Çizilecek görüntünün bölümünü tanımlayan dikdörtgenin yüksekliği |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**, **srcY**, **srcWidth** ve **srcHeight** parametrelerinin belirtildiği ölçüm birimleri |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen konumda çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Görüntünün çizileceği çizim yüzeyinde bir paralelkenar tanımlayan üç nokta içeren bir dizi |
| srcRect | [Rectangle](../../rectangle/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Görüntü için renkleme ve gama bilgilerini belirtir |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) metot

Belirtilen görüntünün belirtilen bölgesini belirtilen konumda çizer.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| x | **float** | Görüntünün çizileceği dikdörtgenin sol üst köşesinin X koordinatı |
| y | **float** | Görüntünün çizileceği dikdörtgenin sol üst köşesinin Y koordinatı |
| srcRect | [RectangleF](../../rectanglef/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** parametresi tarafından kullanılan ölçüm birimleri |

## Ayrıca Bakınız

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