---
title: TextureBrush()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av TextureBrush-klassen som använder den angivna bilden.
type: docs
weight: 1
url: /sv/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor


Skapar en ny instans av [TextureBrush](../) klass som använder den angivna bilden.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | En bild som används av penseln för att fylla insidan av en form |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Anger hur penselobjektet repeteras |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor


Skapar en ny instans av [TextureBrush](../) klass som använder den angivna bilden.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | En bild som används av penseln för att fylla insidan av en form |
| dst_rect | [RectangleF](../../rectanglef/) | Anger den omslutande rektangeln för penseln |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Bildattributen |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor


Skapar en ny instans av [TextureBrush](../) klass som använder den angivna bilden.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | En bild som används av penseln för att fylla insidan av en form |
| dst_rect | [Rectangle](../../rectangle/) | Anger den omslutande rektangeln för penseln |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Bildattributen |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor


Skapar en ny instans av [TextureBrush](../) klass som använder den angivna bilden.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | En bild som används av penseln för att fylla insidan av en form |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Anger hur penselobjektet repeteras |
| dst_rect | [RectangleF](../../rectanglef/) | Anger den omslutande rektangeln för penseln |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor


Skapar en ny instans av [TextureBrush](../) klass som använder den angivna bilden.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | En bild som används av penseln för att fylla insidan av en form |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Anger hur penselobjektet repeteras |
| dst_rect | [Rectangle](../../rectangle/) | Anger den omslutande rektangeln för penseln |

## Se också

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Image](../../image/)
* Klass [TextureBrush](../)
* Klass [RectangleF](../../rectanglef/)
* Klass [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Klass [Rectangle](../../rectangle/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)