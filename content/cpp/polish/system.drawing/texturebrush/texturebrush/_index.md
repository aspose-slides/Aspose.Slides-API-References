---
title: TextureBrush()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nową instancję klasy TextureBrush, która używa określonego obrazu.
type: docs
weight: 1
url: /pl/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) konstruktor

Tworzy nową instancję klasy [TextureBrush](../), która używa określonego obrazu.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz używany przez pędzel do wypełnienia wnętrza kształtu |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Określa, jak obiekt pędzla jest kafelkowany |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) konstruktor

Tworzy nową instancję klasy [TextureBrush](../), która używa określonego obrazu.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz używany przez pędzel do wypełnienia wnętrza kształtu |
| dst_rect | [RectangleF](../../rectanglef/) | Określa prostokąt ograniczający pędzel |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Atrybuty obrazu |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) konstruktor

Tworzy nową instancję klasy [TextureBrush](../), która używa określonego obrazu.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz używany przez pędzel do wypełnienia wnętrza kształtu |
| dst_rect | [Rectangle](../../rectangle/) | Określa prostokąt ograniczający pędzel |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Atrybuty obrazu |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) konstruktor

Tworzy nową instancję klasy [TextureBrush](../), która używa określonego obrazu.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz używany przez pędzel do wypełnienia wnętrza kształtu |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Określa, jak obiekt pędzla jest kafelkowany |
| dst_rect | [RectangleF](../../rectanglef/) | Określa prostokąt ograniczający pędzel |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) konstruktor

Tworzy nową instancję klasy [TextureBrush](../), która używa określonego obrazu.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz używany przez pędzel do wypełnienia wnętrza kształtu |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Określa, jak obiekt pędzla jest kafelkowany |
| dst_rect | [Rectangle](../../rectangle/) | Określa prostokąt ograniczający pędzel |

## Zobacz także

* Wyliczenie [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Image](../../image/)
* Klasa [TextureBrush](../)
* Klasa [RectangleF](../../rectanglef/)
* Klasa [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Klasa [Rectangle](../../rectangle/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)