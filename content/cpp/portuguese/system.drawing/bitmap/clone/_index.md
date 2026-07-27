---
title: Clone()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia do objeto atual.
type: docs
weight: 183
url: /pt/system.drawing/bitmap/clone/
---
## Bitmap::Clone() método


Cria uma cópia do objeto atual.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Valor de Retorno

Uma cópia do objeto atual.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) método


Cria um objeto [Bitmap](../) que representa uma cópia de uma região da imagem bitmap representada pelo objeto atual.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | O retângulo que especifica a região a ser copiada |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | O formato de pixel para o novo [Bitmap](../) |

### Valor de Retorno

O objeto [Bitmap](../) criado

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) método


Cria um objeto [Bitmap](../) que representa uma cópia de uma região da imagem bitmap representada pelo objeto atual.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | O retângulo que especifica a região a ser copiada |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | O formato de pixel para o novo [Bitmap](../) |

### Valor de Retorno

O objeto [Bitmap](../) criado

## Veja Também

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Image](../../image/)
* Classe [Bitmap](../)
* Classe [Rectangle](../../rectangle/)
* Classe [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)