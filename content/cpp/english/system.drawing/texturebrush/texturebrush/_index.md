---
title: TextureBrush()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of TextureBrush class that uses the specified image.
type: docs
weight: 1
url: /system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor


Constructs a new instance of [TextureBrush](../) class that uses the specified image.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifies how the brush object is tiled |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor


Constructs a new instance of [TextureBrush](../) class that uses the specified image.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| dst_rect | [RectangleF](../../rectanglef/) | Specifies the bounding rectangle for the brush |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | The image attributes |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor


Constructs a new instance of [TextureBrush](../) class that uses the specified image.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| dst_rect | [Rectangle](../../rectangle/) | Specifies the bounding rectangle for the brush |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | The image attributes |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor


Constructs a new instance of [TextureBrush](../) class that uses the specified image.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifies how the brush object is tiled |
| dst_rect | [RectangleF](../../rectanglef/) | Specifies the bounding rectangle for the brush |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor


Constructs a new instance of [TextureBrush](../) class that uses the specified image.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifies how the brush object is tiled |
| dst_rect | [Rectangle](../../rectangle/) | Specifies the bounding rectangle for the brush |

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