---
title: TextureBrush()
second_title: Aspose.Slides C++ API-referencia
description: Új példányt hoz létre a TextureBrush osztályból, amely a megadott képet használja.
type: docs
weight: 1
url: /hu/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor


Új példányt hoz létre a [TextureBrush](../) osztályból, amely a megadott képet használja.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A kép, amelyet az ecset a forma belsejének kitöltésére használ |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Meghatározza, hogyan kerül mozaikozásra az ecset objektum |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor


Új példányt hoz létre a [TextureBrush](../) osztályból, amely a megadott képet használja.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A kép, amelyet az ecset a forma belsejének kitöltésére használ |
| dst_rect | [RectangleF](../../rectanglef/) | Meghatározza az ecset határoló téglalapját |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | A kép attribútumai |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor


Új példányt hoz létre a [TextureBrush](../) osztályból, amely a megadott képet használja.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A kép, amelyet az ecset a forma belsejének kitöltésére használ |
| dst_rect | [Rectangle](../../rectangle/) | Meghatározza az ecset határoló téglalapját |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | A kép attribútumai |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor


Új példányt hoz létre a [TextureBrush](../) osztályból, amely a megadott képet használja.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A kép, amelyet az ecset a forma belsejének kitöltésére használ |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Meghatározza, hogyan kerül mozaikozásra az ecset objektum |
| dst_rect | [RectangleF](../../rectanglef/) | Meghatározza az ecset határoló téglalapját |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor


Új példányt hoz létre a [TextureBrush](../) osztályból, amely a megadott képet használja.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A kép, amelyet az ecset a forma belsejének kitöltésére használ |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Meghatározza, hogyan kerül mozaikozásra az ecset objektum |
| dst_rect | [Rectangle](../../rectangle/) | Meghatározza az ecset határoló téglalapját |

## Lásd még

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Image](../../image/)
* Osztály [TextureBrush](../)
* Osztály [RectangleF](../../rectanglef/)
* Osztály [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Osztály [Rectangle](../../rectangle/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)