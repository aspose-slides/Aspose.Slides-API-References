---
title: DrawImage()
second_title: Aspose.Slides for C++ API 參考
description: 未實作。
type: docs
weight: 430
url: /zh-hant/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) 方法

未實作。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 已忽略 |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 已忽略 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 方法

在指定位置繪製指定影像的指定區域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 包含三個點的陣列，這些點定義了繪圖表面上用於繪製影像的平行四邊形 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 定義要繪製之指定影像區域的矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 參數使用的測量單位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定影像的著色與伽瑪資訊 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 方法

在指定位置繪製指定影像的指定區域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | 包含三個點的陣列視圖，這些點定義了繪圖表面上用於繪製影像的平行四邊形 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 定義要繪製之指定影像區域的矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 參數使用的測量單位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定影像的著色與伽瑪資訊 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 方法

在指定位置繪製指定影像的指定區域。

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | 包含三個點的堆疊陣列，這些點定義了繪圖表面上用於繪製影像的平行四邊形 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 定義要繪製之指定影像區域的矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 參數使用的測量單位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定影像的著色與伽瑪資訊 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) 方法

在指定位置繪製指定影像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| x | int | 繪製影像左上角的 X 座標 |
| y | int | 繪製影像左上角的 Y 座標 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) 方法

在指定位置繪製指定影像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| x | **float** | 繪製影像左上角的 X 座標 |
| y | **float** | 繪製影像左上角的 Y 座標 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) 方法

在指定位置繪製指定影像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| pt | [Point](../../point/) | 繪製影像左上角的位置 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) 方法

在指定位置繪製指定影像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| pt | [PointF](../../pointf/) | 繪製影像左上角的位置 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) 方法

將指定影像繪製至指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| x | int | 要繪製影像之矩形左上角的 X 座標 |
| y | int | 要繪製影像之矩形左上角的 Y 座標 |
| width | int | 要繪製影像之矩形左上角的寬度 |
| height | int | 要繪製影像之矩形左上角的高度 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) 方法

將指定影像繪製至指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| x | **float** | 要繪製影像之矩形左上角的 X 座標 |
| y | **float** | 要繪製影像之矩形左上角的 Y 座標 |
| width | **float** | 要繪製影像之矩形左上角的寬度 |
| height | **float** | 要繪製影像之矩形左上角的高度 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) 方法

在指定位置繪製指定影像的指定區域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destRect | [RectangleF](../../rectanglef/) | 用於繪製影像的矩形 |
| srcRect | [RectangleF](../../rectanglef/) | 定義要繪製之指定影像區域的矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 參數使用的測量單位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) 方法

在指定位置繪製指定影像的指定區域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destRect | [Rectangle](../../rectangle/) | 用於繪製影像的矩形 |
| srcRect | [Rectangle](../../rectangle/) | 定義要繪製之指定影像區域的矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 參數使用的測量單位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) 方法

在指定位置繪製指定影像的指定區域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| x | int | 要繪製影像之矩形左上角的 X 座標 |
| y | int | 要繪製影像之矩形左上角的 Y 座標 |
| srcRect | [Rectangle](../../rectangle/) | 定義要繪製之指定影像區域的矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 參數使用的測量單位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) 方法

在指定位置繪製指定影像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| rect | const [Rectangle](../../rectangle/)\& | 用於繪製影像的矩形 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) 方法

在指定位置繪製指定影像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| rect | const [RectangleF](../../rectanglef/)\& | 用於繪製影像的矩形 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 方法

將指定影像的指定區域繪製至指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destRect | [Rectangle](../../rectangle/) | 用於繪製影像的矩形 |
| srcX | int | 指定要繪製之影像區塊之矩形左上角的 X 座標 |
| srcY | int | 指定要繪製之影像區塊之矩形左上角的 Y 座標 |
| srcWidth | int | 指定要繪製之影像區塊之矩形左上角的寬度 |
| srcHeight | int | 指定要繪製之影像區塊之矩形左上角的高度 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**、**srcY**、**srcWidth** 與 **srcHeight** 參數所使用的測量單位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定影像的著色與伽瑪資訊 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 方法

將指定影像的指定區域繪製至指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destRect | [Rectangle](../../rectangle/) | 用於繪製影像的矩形 |
| srcX | **float** | 指定要繪製之影像區塊之矩形左上角的 X 座標 |
| srcY | **float** | 指定要繪製之影像區塊之矩形左上角的 Y 座標 |
| srcWidth | **float** | 指定要繪製之影像區塊之矩形左上角的寬度 |
| srcHeight | **float** | 指定要繪製之影像區塊之矩形左上角的高度 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**、**srcY**、**srcWidth** 與 **srcHeight** 參數所使用的測量單位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定影像的著色與伽瑪資訊 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) 方法

將指定影像的指定區域繪製至指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destRect | [Rectangle](../../rectangle/) | 用於繪製影像的矩形 |
| srcX | int | 指定要繪製之影像區塊之矩形左上角的 X 座標 |
| srcY | int | 指定要繪製之影像區塊之矩形左上角的 Y 座標 |
| srcWidth | int | 指定要繪製之影像區塊之矩形左上角的寬度 |
| srcHeight | int | 指定要繪製之影像區塊之矩形左上角的高度 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**、**srcY**、**srcWidth** 與 **srcHeight** 參數所使用的測量單位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) 方法

將指定影像的指定區域繪製至指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destRect | [Rectangle](../../rectangle/) | 用於繪製影像的矩形 |
| srcX | **float** | 指定要繪製之影像區塊之矩形左上角的 X 座標 |
| srcY | **float** | 指定要繪製之影像區塊之矩形左上角的 Y 座標 |
| srcWidth | **float** | 指定要繪製之影像區塊之矩形左上角的寬度 |
| srcHeight | **float** | 指定要繪製之影像區塊之矩形左上角的高度 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**、**srcY**、**srcWidth** 與 **srcHeight** 參數所使用的測量單位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) 方法

未實作。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) 方法

未實作。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) 方法

未實作。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) 方法

未實作。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) 方法

未實作。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) 方法

未實作。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) 方法

未實作。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) 方法

在指定位置繪製指定影像的指定區域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 包含三個點的陣列，這些點定義了繪圖表面上用於繪製影像的平行四邊形 |
| srcRect | [Rectangle](../../rectangle/) | 定義要繪製之指定影像區域的矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 參數使用的測量單位 |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 指定影像的著色與伽瑪資訊 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) 方法

在指定位置繪製指定影像的指定區域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| x | **float** | 要繪製影像之矩形左上角的 X 座標 |
| y | **float** | 要繪製影像之矩形左上角的 Y 座標 |
| srcRect | [RectangleF](../../rectanglef/) | 定義要繪製之指定影像區域的矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 參數使用的測量單位 |

## 另請參閱

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