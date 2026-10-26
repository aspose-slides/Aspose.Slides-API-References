---
title: Bitmap()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye un nuevo objeto Bitmap a partir de la imagen existente especificada.
type: docs
weight: 1
url: /es/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor

Construye un nuevo objeto [Bitmap](../) a partir de la imagen existente especificada.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen existente para crear la imagen bitmap a partir de ella |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor

Construye un nuevo objeto [Bitmap](../) a partir del flujo especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flujo que contiene datos de imagen |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(const String\&) constructor

Construye un nuevo objeto [Bitmap](../) a partir del archivo especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Un nombre del archivo que contiene datos de imagen |

## Bitmap::Bitmap(const String\&, bool) constructor

Construye un nuevo objeto [Bitmap](../) a partir del archivo especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Un nombre del archivo que contiene datos de imagen |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor

Construye un nuevo objeto [Bitmap](../) que representa una imagen bitmap con el ancho, la altura, el formato de píxel y los datos de píxel especificados.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen |
| height | int | La altura de la imagen |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | El formato de píxel de la imagen |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor

Construye un nuevo objeto [Bitmap](../) a partir de la imagen existente especificada, escalada al tamaño indicado.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen existente para crear la imagen bitmap a partir de ella |
| size | const [Size](../../size/)\& | El tamaño de la nueva imagen |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor

Construye un nuevo objeto [Bitmap](../) a partir de la imagen existente especificada, con el ancho y la altura escalados a los valores indicados.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | La imagen existente para crear la imagen bitmap a partir de ella |
| width | int | Ancho de la nueva imagen |
| height | int | Altura de la nueva imagen |

## Ver también

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)