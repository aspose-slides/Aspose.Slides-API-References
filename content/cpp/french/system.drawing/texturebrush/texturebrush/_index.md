---
title: TextureBrush()
second_title: Référence de l'API Aspose.Slides for C++
description: Construit une nouvelle instance de la classe TextureBrush qui utilise l'image spécifiée.
type: docs
weight: 1
url: /fr/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor

Construit une nouvelle instance de la classe [TextureBrush](../) qui utilise l'image spécifiée.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Une image utilisée par le pinceau pour remplir l'intérieur d'une forme |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Spécifie comment l'objet pinceau est assemblé en mosaïque |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Construit une nouvelle instance de la classe [TextureBrush](../) qui utilise l'image spécifiée.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Une image utilisée par le pinceau pour remplir l'intérieur d'une forme |
| dst_rect | [RectangleF](../../rectanglef/) | Spécifie le rectangle englobant du pinceau |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Les attributs de l'image |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Construit une nouvelle instance de la classe [TextureBrush](../) qui utilise l'image spécifiée.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Une image utilisée par le pinceau pour remplir l'intérieur d'une forme |
| dst_rect | [Rectangle](../../rectangle/) | Spécifie le rectangle englobant du pinceau |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Les attributs de l'image |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor

Construit une nouvelle instance de la classe [TextureBrush](../) qui utilise l'image spécifiée.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Une image utilisée par le pinceau pour remplir l'intérieur d'une forme |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Spécifie comment l'objet pinceau est assemblé en mosaïque |
| dst_rect | [RectangleF](../../rectanglef/) | Spécifie le rectangle englobant du pinceau |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor

Construit une nouvelle instance de la classe [TextureBrush](../) qui utilise l'image spécifiée.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Une image utilisée par le pinceau pour remplir l'intérieur d'une forme |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Spécifie comment l'objet pinceau est assemblé en mosaïque |
| dst_rect | [Rectangle](../../rectangle/) | Spécifie le rectangle englobant du pinceau |

## Voir aussi

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [TextureBrush](../)
* Class [RectangleF](../../rectanglef/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)