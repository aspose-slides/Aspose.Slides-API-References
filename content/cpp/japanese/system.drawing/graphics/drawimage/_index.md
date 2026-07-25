---
title: DrawImage()
second_title: Aspose.Slides for C++ API リファレンス
description: 未実装です。
type: docs
weight: 430
url: /ja/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) メソッド

未実装。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 無視 |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 無視 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) メソッド

指定された画像の指定された領域を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 画像を描画するために描画面上に平行四辺形を定義する3つの点を含む配列 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 描画する画像の領域を定義する矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** パラメータで使用される測定単位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 画像のカラーリングとガンマ情報を指定します |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) メソッド

指定された画像の指定された領域を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | 画像を描画するために描画面上に平行四辺形を定義する3つの点を含む配列ビュー |
| srcRect | const [RectangleF](../../rectanglef/)\& | 描画する画像の領域を定義する矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** パラメータで使用される測定単位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 画像のカラーリングとガンマ情報を指定します |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) メソッド

指定された画像の指定された領域を指定された位置に描画します。

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | 画像を描画するために描画面上に平行四辺形を定義する3つの点を含むスタック配列 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 描画する画像の領域を定義する矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** パラメータで使用される測定単位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 画像のカラーリングとガンマ情報を指定します |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) メソッド

指定された画像を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| x | int | 描画された画像の左上隅のX座標 |
| y | int | 描画された画像の左上隅のY座標 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) メソッド

指定された画像を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| x | **float** | 描画された画像の左上隅のX座標 |
| y | **float** | 描画された画像の左上隅のY座標 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) メソッド

指定された画像を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| pt | [Point](../../point/) | 描画された画像の左上隅の位置 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) メソッド

指定された画像を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| pt | [PointF](../../pointf/) | 描画された画像の左上隅の位置 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) メソッド

指定された画像を指定された矩形に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| x | int | 描画する矩形の左上隅のX座標 |
| y | int | 描画する矩形の左上隅のY座標 |
| width | int | 描画する矩形の幅 |
| height | int | 描画する矩形の高さ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) メソッド

指定された画像を指定された矩形に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| x | **float** | 描画する矩形の左上隅のX座標 |
| y | **float** | 描画する矩形の左上隅のY座標 |
| width | **float** | 描画する矩形の幅 |
| height | **float** | 描画する矩形の高さ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) メソッド

指定された画像の指定された領域を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destRect | [RectangleF](../../rectanglef/) | 画像を描画する矩形 |
| srcRect | [RectangleF](../../rectanglef/) | 描画する画像の領域を定義する矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** パラメータで使用される測定単位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) メソッド

指定された画像の指定された領域を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destRect | [Rectangle](../../rectangle/) | 画像を描画する矩形 |
| srcRect | [Rectangle](../../rectangle/) | 描画する画像の領域を定義する矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** パラメータで使用される測定単位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) メソッド

指定された画像の指定された領域を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| x | int | 描画する矩形の左上隅のX座標 |
| y | int | 描画する矩形の左上隅のY座標 |
| srcRect | [Rectangle](../../rectangle/) | 描画する画像の領域を定義する矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** パラメータで使用される測定単位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) メソッド

指定された画像を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| rect | const [Rectangle](../../rectangle/)\& | 画像を描画する矩形 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) メソッド

指定された画像を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| rect | const [RectangleF](../../rectanglef/)\& | 画像を描画する矩形 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) メソッド

指定された画像の指定された領域を指定された矩形に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destRect | [Rectangle](../../rectangle/) | 画像を描画する矩形 |
| srcX | int | 描画する画像の一部を指定する矩形の左上隅のX座標 |
| srcY | int | 描画する画像の一部を指定する矩形の左上隅のY座標 |
| srcWidth | int | 描画する画像の一部を指定する矩形の幅 |
| srcHeight | int | 描画する画像の一部を指定する矩形の高さ |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | パラメータ **srcX**、**srcY**、**srcWidth**、**srcHeight** が指定されている測定単位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 画像のカラーリングとガンマ情報を指定します |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) メソッド

指定された画像の指定された領域を指定された矩形に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destRect | [Rectangle](../../rectangle/) | 画像を描画する矩形 |
| srcX | **float** | 描画する画像の一部を指定する矩形の左上隅のX座標 |
| srcY | **float** | 描画する画像の一部を指定する矩形の左上隅のY座標 |
| srcWidth | **float** | 描画する画像の一部を指定する矩形の幅 |
| srcHeight | **float** | 描画する画像の一部を指定する矩形の高さ |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | パラメータ **srcX**、**srcY**、**srcWidth**、**srcHeight** が指定されている測定単位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 画像のカラーリングとガンマ情報を指定します |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) メソッド

指定された画像の指定された領域を指定された矩形に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destRect | [Rectangle](../../rectangle/) | 画像を描画する矩形 |
| srcX | int | 描画する画像の一部を指定する矩形の左上隅のX座標 |
| srcY | int | 描画する画像の一部を指定する矩形の左上隅のY座標 |
| srcWidth | int | 描画する画像の一部を指定する矩形の幅 |
| srcHeight | int | 描画する画像の一部を指定する矩形の高さ |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | パラメータ **srcX**、**srcY**、**srcWidth**、**srcHeight** が指定されている測定単位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) メソッド

指定された画像の指定された領域を指定された矩形に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destRect | [Rectangle](../../rectangle/) | 画像を描画する矩形 |
| srcX | **float** | 描画する画像の一部を指定する矩形の左上隅のX座標 |
| srcY | **float** | 描画する画像の一部を指定する矩形の左上隅のY座標 |
| srcWidth | **float** | 描画する画像の一部を指定する矩形の幅 |
| srcHeight | **float** | 描画する画像の一部を指定する矩形の高さ |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | パラメータ **srcX**、**srcY**、**srcWidth**、**srcHeight** が指定されている測定単位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) メソッド

未実装。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) メソッド

未実装。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) メソッド

未実装。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) メソッド

未実装。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) メソッド

未実装。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) メソッド

未実装。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) メソッド

未実装。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) メソッド

指定された画像の指定された領域を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 画像を描画するために描画面上に平行四辺形を定義する3つの点を含む配列 |
| srcRect | [Rectangle](../../rectangle/) | 描画する画像の領域を定義する矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** パラメータで使用される測定単位 |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 画像のカラーリングとガンマ情報を指定します |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) メソッド

指定された画像の指定された領域を指定された位置に描画します。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| x | **float** | 描画する矩形の左上隅のX座標 |
| y | **float** | 描画する矩形の左上隅のY座標 |
| srcRect | [RectangleF](../../rectanglef/) | 描画する画像の領域を定義する矩形 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** パラメータで使用される測定単位 |

## 参照

* 列挙型 [GraphicsUnit](../../graphicsunit/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* 型定義 [DrawImageAbort](../drawimageabort/)
* クラス [Image](../../image/)
* クラス [Point](../../point/)
* クラス [Graphics](../)
* クラス [PointF](../../pointf/)
* クラス [RectangleF](../../rectanglef/)
* クラス [Rectangle](../../rectangle/)
* クラス [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)