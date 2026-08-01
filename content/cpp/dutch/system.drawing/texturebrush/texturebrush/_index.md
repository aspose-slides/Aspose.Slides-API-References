---
title: TextureBrush()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de TextureBrush-klasse die de opgegeven afbeelding gebruikt.
type: docs
weight: 1
url: /nl/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor


Construeert een nieuw exemplaar van de [TextureBrush](../) klasse die de opgegeven afbeelding gebruikt.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Een afbeelding die door de penseel wordt gebruikt om het binnenste van een vorm te vullen |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specificeert hoe het penseelobject wordt getegeld |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor


Construeert een nieuw exemplaar van de [TextureBrush](../) klasse die de opgegeven afbeelding gebruikt.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Een afbeelding die door de penseel wordt gebruikt om het binnenste van een vorm te vullen |
| dst_rect | [RectangleF](../../rectanglef/) | Specificeert de begrenzende rechthoek voor het penseel |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | De afbeelding-eigenschappen |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor


Construeert een nieuw exemplaar van de [TextureBrush](../) klasse die de opgegeven afbeelding gebruikt.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Een afbeelding die door de penseel wordt gebruikt om het binnenste van een vorm te vullen |
| dst_rect | [Rectangle](../../rectangle/) | Specificeert de begrenzende rechthoek voor het penseel |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | De afbeelding-eigenschappen |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor


Construeert een nieuw exemplaar van de [TextureBrush](../) klasse die de opgegeven afbeelding gebruikt.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Een afbeelding die door de penseel wordt gebruikt om het binnenste van een vorm te vullen |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specificeert hoe het penseelobject wordt getegeld |
| dst_rect | [RectangleF](../../rectanglef/) | Specificeert de begrenzende rechthoek voor het penseel |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor


Construeert een nieuw exemplaar van de [TextureBrush](../) klasse die de opgegeven afbeelding gebruikt.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Een afbeelding die door de penseel wordt gebruikt om het binnenste van een vorm te vullen |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specificeert hoe het penseelobject wordt getegeld |
| dst_rect | [Rectangle](../../rectangle/) | Specificeert de begrenzende rechthoek voor het penseel |

## Zie ook

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [TextureBrush](../)
* Class [RectangleF](../../rectanglef/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)