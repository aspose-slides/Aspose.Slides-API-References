---
title: TextureBrush()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz der TextureBrush-Klasse, die das angegebene Bild verwendet.
type: docs
weight: 1
url: /de/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor

Konstruiert eine neue Instanz der [TextureBrush](../) Klasse, die das angegebene Bild verwendet.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Ein Bild, das vom Pinsel verwendet wird, um das Innere einer Form zu füllen |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Gibt an, wie das Pinselobjekt gekachelt wird |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Konstruiert eine neue Instanz der [TextureBrush](../) Klasse, die das angegebene Bild verwendet.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Ein Bild, das vom Pinsel verwendet wird, um das Innere einer Form zu füllen |
| dst_rect | [RectangleF](../../rectanglef/) | Gibt das Begrenzungsrechteck für den Pinsel an |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Die Bildeigenschaften |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Konstruiert eine neue Instanz der [TextureBrush](../) Klasse, die das angegebene Bild verwendet.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Ein Bild, das vom Pinsel verwendet wird, um das Innere einer Form zu füllen |
| dst_rect | [Rectangle](../../rectangle/) | Gibt das Begrenzungsrechteck für den Pinsel an |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Die Bildeigenschaften |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor

Konstruiert eine neue Instanz der [TextureBrush](../) Klasse, die das angegebene Bild verwendet.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Ein Bild, das vom Pinsel verwendet wird, um das Innere einer Form zu füllen |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Gibt an, wie das Pinselobjekt gekachelt wird |
| dst_rect | [RectangleF](../../rectanglef/) | Gibt das Begrenzungsrechteck für den Pinsel an |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor

Konstruiert eine neue Instanz der [TextureBrush](../) Klasse, die das angegebene Bild verwendet.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Ein Bild, das vom Pinsel verwendet wird, um das Innere einer Form zu füllen |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Gibt an, wie das Pinselobjekt gekachelt wird |
| dst_rect | [Rectangle](../../rectangle/) | Gibt das Begrenzungsrechteck für den Pinsel an |

## Siehe auch

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Image](../../image/)
* Klasse [TextureBrush](../)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Klasse [Rectangle](../../rectangle/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)