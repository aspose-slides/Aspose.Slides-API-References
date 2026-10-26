---
title: TextureBrush()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vytvoří novou instanci třídy TextureBrush, která používá zadaný obrázek.
type: docs
weight: 1
url: /cs/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor

Vytvoří novou instanci třídy [TextureBrush](../), která používá zadaný obrázek.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek používaný štětcem k vyplnění vnitřku tvaru |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Určuje, jak je objekt štětce dlaždicován |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Vytvoří novou instanci třídy [TextureBrush](../), která používá zadaný obrázek.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek používaný štětcem k vyplnění vnitřku tvaru |
| dst_rect | [RectangleF](../../rectanglef/) | Určuje ohraničující obdélník pro štětec |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Atributy obrázku |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Vytvoří novou instanci třídy [TextureBrush](../), která používá zadaný obrázek.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek používaný štětcem k vyplnění vnitřku tvaru |
| dst_rect | [Rectangle](../../rectangle/) | Určuje ohraničující obdélník pro štětec |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Atributy obrázku |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor

Vytvoří novou instanci třídy [TextureBrush](../), která používá zadaný obrázek.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek používaný štětcem k vyplnění vnitřku tvaru |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Určuje, jak je objekt štětce dlaždicován |
| dst_rect | [RectangleF](../../rectanglef/) | Určuje ohraničující obdélník pro štětec |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor

Vytvoří novou instanci třídy [TextureBrush](../), která používá zadaný obrázek.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek používaný štětcem k vyplnění vnitřku tvaru |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Určuje, jak je objekt štětce dlaždicován |
| dst_rect | [Rectangle](../../rectangle/) | Určuje ohraničující obdélník pro štětec |

## Viz také

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Image](../../image/)
* Třída [TextureBrush](../)
* Třída [RectangleF](../../rectanglef/)
* Třída [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Třída [Rectangle](../../rectangle/)
* Jmenný prostor [System::Drawing](../../)
* Library [Aspose.Slides](../../../)