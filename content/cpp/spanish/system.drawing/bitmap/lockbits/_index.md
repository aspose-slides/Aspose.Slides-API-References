---
title: LockBits()
second_title: Referencia de API de Aspose.Slides para C++
description: Bloquea un Bitmap en la memoria del sistema.
type: docs
weight: 118
url: /es/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method

Bloquea un [Bitmap](../) en la memoria del sistema.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectángulo que especifica la región de la imagen a bloquear |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Especifica el nivel de acceso al bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | El formato de datos de este bitmap |

### Valor de retorno

Un puntero compartido a un objeto BitmapData que contiene información sobre la operación de bloqueo realizada

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method

Bloquea un [Bitmap](../) en la memoria del sistema.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectángulo que especifica la región de la imagen a bloquear |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Especifica el nivel de acceso al bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | El formato de datos de este bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Contiene información sobre la operación de bloqueo |

### Valor de retorno

Un puntero compartido a un objeto BitmapData que contiene información sobre la operación de bloqueo realizada

## Ver también

* Enumeración [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enumeración [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Definición de tipo [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Clase [Rectangle](../../rectangle/)
* Clase [Bitmap](../)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)