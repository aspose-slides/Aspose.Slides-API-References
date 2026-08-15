---
title: TextureBrush()
second_title: Aspose.Slides for C++ API 參考
description: 建立使用指定影像的 TextureBrush 類別的新實例。
type: docs
weight: 1
url: /zh-hant/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) 建構函式

建立使用指定影像的 [TextureBrush](../) 類別的新實例。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用於填充形狀內部的影像 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | 指定畫刷物件的平鋪方式 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) 建構函式

建立使用指定影像的 [TextureBrush](../) 類別的新實例。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用於填充形狀內部的影像 |
| dst_rect | [RectangleF](../../rectanglef/) | 指定畫刷的邊界矩形 |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 影像屬性 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) 建構函式

建立使用指定影像的 [TextureBrush](../) 類別的新實例。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用於填充形狀內部的影像 |
| dst_rect | [Rectangle](../../rectangle/) | 指定畫刷的邊界矩形 |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 影像屬性 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) 建構函式

建立使用指定影像的 [TextureBrush](../) 類別的新實例。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用於填充形狀內部的影像 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | 指定畫刷物件的平鋪方式 |
| dst_rect | [RectangleF](../../rectanglef/) | 指定畫刷的邊界矩形 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) 建構函式

建立使用指定影像的 [TextureBrush](../) 類別的新實例。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用於填充形狀內部的影像 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | 指定畫刷物件的平鋪方式 |
| dst_rect | [Rectangle](../../rectangle/) | 指定畫刷的邊界矩形 |

## 另請參閱

* 列舉 [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Image](../../image/)
* 類別 [TextureBrush](../)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* 類別 [Rectangle](../../rectangle/)
* 命名空間 [System::Drawing](../../)
* 程式庫 [Aspose.Slides](../../../)