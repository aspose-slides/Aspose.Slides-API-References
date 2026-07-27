---
title: TextureBrush()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase TextureBrush que usa la imagen especificada.
type: docs
weight: 1
url: /es/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor

Construye una nueva instancia de la clase [TextureBrush](../) que usa la imagen especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Una imagen utilizada por el pincel para rellenar el interior de una forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Especifica cómo se repite el objeto pincel |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Construye una nueva instancia de la clase [TextureBrush](../) que usa la imagen especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Una imagen utilizada por el pincel para rellenar el interior de una forma |
| dst_rect | [RectangleF](../../rectanglef/) | Especifica el rectángulo delimitador del pincel |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Los atributos de la imagen |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

Construye una nueva instancia de la clase [TextureBrush](../) que usa la imagen especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Una imagen utilizada por el pincel para rellenar el interior de una forma |
| dst_rect | [Rectangle](../../rectangle/) | Especifica el rectángulo delimitador del pincel |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Los atributos de la imagen |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor

Construye una nueva instancia de la clase [TextureBrush](../) que usa la imagen especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Una imagen utilizada por el pincel para rellenar el interior de una forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Especifica cómo se repite el objeto pincel |
| dst_rect | [RectangleF](../../rectanglef/) | Especifica el rectángulo delimitador del pincel |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor

Construye una nueva instancia de la clase [TextureBrush](../) que usa la imagen especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Una imagen utilizada por el pincel para rellenar el interior de una forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Especifica cómo se repite el objeto pincel |
| dst_rect | [Rectangle](../../rectangle/) | Especifica el rectángulo delimitador del pincel |

## Ver también

* Enumeración [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [Image](../../image/)
* Clase [TextureBrush](../)
* Clase [RectangleF](../../rectanglef/)
* Clase [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Clase [Rectangle](../../rectangle/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)