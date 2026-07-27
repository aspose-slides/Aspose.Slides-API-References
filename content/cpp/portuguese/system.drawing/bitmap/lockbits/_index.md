---
title: LockBits()
second_title: Referência da API Aspose.Slides para C++
description: Bloqueia um Bitmap na memória do sistema.
type: docs
weight: 118
url: /pt/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) método

Bloqueia um [Bitmap](../) na memória do sistema.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Um retângulo que especifica a região da imagem a ser bloqueada |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Especifica o nível de acesso ao bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | O formato de dados deste bitmap |

### Valor de Retorno

Um ponteiro compartilhado para um objeto BitmapData que contém informações sobre a operação de bloqueio realizada

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) método

Bloqueia um [Bitmap](../) na memória do sistema.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Um retângulo que especifica a região da imagem a ser bloqueada |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Especifica o nível de acesso ao bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | O formato de dados deste bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Contém informações sobre a operação de bloqueio |

### Valor de Retorno

Um ponteiro compartilhado para um objeto BitmapData que contém informações sobre a operação de bloqueio realizada

## Veja Também

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)