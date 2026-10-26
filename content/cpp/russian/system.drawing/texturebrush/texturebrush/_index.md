---
title: TextureBrush()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр класса TextureBrush, использующий указанное изображение.
type: docs
weight: 1
url: /ru/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor

Создает новый экземпляр класса [TextureBrush](../) , использующий указанное изображение.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение, используемое кистью для заполнения внутренней части фигуры |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Указывает, как объект кисти будет разложен по плиткам |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Создает новый экземпляр класса [TextureBrush](../) , использующий указанное изображение.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение, используемое кистью для заполнения внутренней части фигуры |
| dst_rect | [RectangleF](../../rectanglef/) | Указывает ограничивающий прямоугольник для кисти |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Атрибуты изображения |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Создает новый экземпляр класса [TextureBrush](../) , использующий указанное изображение.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение, используемое кистью для заполнения внутренней части фигуры |
| dst_rect | [Rectangle](../../rectangle/) | Указывает ограничивающий прямоугольник для кисти |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Атрибуты изображения |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor

Создает новый экземпляр класса [TextureBrush](../) , использующий указанное изображение.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение, используемое кистью для заполнения внутренней части фигуры |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Указывает, как объект кисти будет разложен по плиткам |
| dst_rect | [RectangleF](../../rectanglef/) | Указывает ограничивающий прямоугольник для кисти |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor

Создает новый экземпляр класса [TextureBrush](../) , использующий указанное изображение.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение, используемое кистью для заполнения внутренней части фигуры |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Указывает, как объект кисти будет разложен по плиткам |
| dst_rect | [Rectangle](../../rectangle/) | Указывает ограничивающий прямоугольник для кисти |

## See Also

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [TextureBrush](../)
* Class [RectangleF](../../rectanglef/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)