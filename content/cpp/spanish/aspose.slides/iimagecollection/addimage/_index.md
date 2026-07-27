---
title: AddImage()
second_title: Referencia de API de Aspose.Slides para C++
description: Añade una imagen a una presentación.
type: docs
weight: 14
url: /es/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) método

Añade una imagen a una presentación.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Imagen a añadir. |

### Valor de retorno

Imagen agregada.

## Observaciones

Este método convierte archivos metafile WMF/EMF a una imagen PNG raster antes de insertarlos en una presentación.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) método

Añade una imagen desde un flujo de memoria.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Flujo de memoria. |

### Valor de retorno

Imagen agregada.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) método

Añade una imagen a una presentación desde un flujo.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo del que se añadirá la imagen. |

### Valor de retorno

Imagen agregada.

## Observaciones

Este método puede añadir archivos metafile WMF/EMF a una presentación sin convertirlos a una imagen PNG raster.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método

Crea y añade una imagen a una presentación desde un flujo.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo del que se añadirá el archivo de imagen. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | El comportamiento que se aplicará al flujo. |

### Valor de retorno

Añadido [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) método

Añade una imagen a una presentación desde un búfer especificado.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Búfer. |

### Valor de retorno

Imagen agregada.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) método

Añade una copia de una imagen de otra presentación.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Imagen de origen. |

### Valor de retorno

Imagen agregada.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) método

Añade una imagen a una presentación desde un objeto SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objeto de imagen SVG [ISvgImage](../../isvgimage/) |

### Valor de retorno

Imagen agregada.

## Ver también

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)