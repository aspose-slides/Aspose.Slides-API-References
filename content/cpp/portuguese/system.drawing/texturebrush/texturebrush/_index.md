---
title: TextureBrush()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância da classe TextureBrush que usa a imagem especificada.
type: docs
weight: 1
url: /pt/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) construtor

Constrói uma nova instância da classe [TextureBrush](../) que usa a imagem especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Uma imagem usada pelo brush para preencher o interior de uma forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Especifica como o objeto brush é repetido |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) construtor

Constrói uma nova instância da classe [TextureBrush](../) que usa a imagem especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Uma imagem usada pelo brush para preencher o interior de uma forma |
| dst_rect | [RectangleF](../../rectanglef/) | Especifica o retângulo delimitador para o brush |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Os atributos da imagem |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) construtor

Constrói uma nova instância da classe [TextureBrush](../) que usa a imagem especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Uma imagem usada pelo brush para preencher o interior de uma forma |
| dst_rect | [Rectangle](../../rectangle/) | Especifica o retângulo delimitador para o brush |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Os atributos da imagem |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) construtor

Constrói uma nova instância da classe [TextureBrush](../) que usa a imagem especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Uma imagem usada pelo brush para preencher o interior de uma forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Especifica como o objeto brush é repetido |
| dst_rect | [RectangleF](../../rectanglef/) | Especifica o retângulo delimitador para o brush |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) construtor

Constrói uma nova instância da classe [TextureBrush](../) que usa a imagem especificada.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Uma imagem usada pelo brush para preencher o interior de uma forma |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Especifica como o objeto brush é repetido |
| dst_rect | [Rectangle](../../rectangle/) | Especifica o retângulo delimitador para o brush |

## Veja Também

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [TextureBrush](../)
* Class [RectangleF](../../rectanglef/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)