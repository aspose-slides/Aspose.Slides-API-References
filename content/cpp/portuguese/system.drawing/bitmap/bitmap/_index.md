---
title: Bitmap()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um novo objeto Bitmap a partir da imagem existente especificada.
type: docs
weight: 1
url: /pt/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) construtor

Constrói um novo objeto [Bitmap](../) a partir da imagem existente especificada.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem existente a partir da qual criar a imagem bitmap |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) construtor

Constrói um novo objeto [Bitmap](../) a partir do stream especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Um stream que contém dados de imagem |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(const String\&) construtor

Constrói um novo objeto [Bitmap](../) a partir do arquivo especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Um nome de arquivo que contém dados de imagem |

## Bitmap::Bitmap(const String\&, bool) construtor

Constrói um novo objeto [Bitmap](../) a partir do arquivo especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Um nome de arquivo que contém dados de imagem |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) construtor

Constrói um novo objeto [Bitmap](../) que representa uma imagem bitmap com a largura, altura, formato de pixel e dados de pixel especificados.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | int | A largura da imagem |
| height | int | A altura da imagem |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | O formato de pixel da imagem |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) construtor

Constrói um novo objeto [Bitmap](../) a partir da imagem existente especificada, dimensionada ao tamanho especificado.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem existente a partir da qual criar a imagem bitmap |
| size | const [Size](../../size/)\& | O tamanho da nova imagem |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) construtor

Constrói um novo objeto [Bitmap](../) a partir da imagem existente especificada com largura e altura dimensionadas aos valores especificados.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem existente a partir da qual criar a imagem bitmap |
| width | int | Largura da nova imagem |
| height | int | Altura da nova imagem |

## Veja Também

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Image](../../image/)
* Classe [Bitmap](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Classe [Size](../../size/)
* Namespace [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)