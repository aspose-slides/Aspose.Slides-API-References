---
title: TextureBrush()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova istanza della classe TextureBrush che utilizza l'immagine specificata.
type: docs
weight: 1
url: /it/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) costruttore

Crea una nuova istanza della classe [TextureBrush](../) che utilizza l'immagine specificata.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Un'immagine usata dal pennello per riempire l'interno di una forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifica come l'oggetto pennello è piastrellato |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) costruttore

Crea una nuova istanza della classe [TextureBrush](../) che utilizza l'immagine specificata.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Un'immagine usata dal pennello per riempire l'interno di una forma |
| dst_rect | [RectangleF](../../rectanglef/) | Specifica il rettangolo di delimitazione per il pennello |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Gli attributi dell'immagine |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) costruttore

Crea una nuova istanza della classe [TextureBrush](../) che utilizza l'immagine specificata.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Un'immagine usata dal pennello per riempire l'interno di una forma |
| dst_rect | [Rectangle](../../rectangle/) | Specifica il rettangolo di delimitazione per il pennello |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Gli attributi dell'immagine |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) costruttore

Crea una nuova istanza della classe [TextureBrush](../) che utilizza l'immagine specificata.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Un'immagine usata dal pennello per riempire l'interno di una forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifica come l'oggetto pennello è piastrellato |
| dst_rect | [RectangleF](../../rectanglef/) | Specifica il rettangolo di delimitazione per il pennello |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) costruttore

Crea una nuova istanza della classe [TextureBrush](../) che utilizza l'immagine specificata.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Un'immagine usata dal pennello per riempire l'interno di una forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifica come l'oggetto pennello è piastrellato |
| dst_rect | [Rectangle](../../rectangle/) | Specifica il rettangolo di delimitazione per il pennello |

## Vedi anche

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Image](../../image/)
* Classe [TextureBrush](../)
* Classe [RectangleF](../../rectanglef/)
* Classe [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Classe [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)