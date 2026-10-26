---
title: AddImage()
second_title: Referencia de la API de Aspose.Slides para C++
description: Añade una copia de una imagen de otra presentación.
type: docs
weight: 53
url: /es/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) método


Añade una copia de una imagen de otra presentación.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Imagen origen. |

### Valor devuelto

Imagen añadida.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) método


Añade una imagen a una presentación.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Imagen a añadir. |

### Valor devuelto

Imagen añadida.

## Comentarios


Este método convierte los metarchivos WMF/EMF a imágenes PNG raster antes de insertarlos en una presentación.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) método


Añade una imagen a una presentación desde un flujo.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Flujo del que se añadirá la imagen. |

### Valor devuelto

Imagen añadida.

## Comentarios


Este método puede añadir metarchivos WMF/EMF a una presentación sin convertirlos a imágenes PNG raster.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) método


Añade una imagen a una presentación desde un flujo.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo del que se añadirá la imagen. |

### Valor devuelto

Imagen añadida.

## Comentarios


Este método puede añadir metarchivos WMF/EMF a una presentación sin convertirlos a imágenes PNG raster.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método


Crea y añade una imagen a una presentación desde un flujo.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo del que se añadirá el archivo de imagen. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | El comportamiento que se aplicará al flujo. |

### Valor devuelto

Añadido [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) método


Añade una imagen a una presentación desde un búfer especificado.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Búfer. |

### Valor devuelto

Imagen añadida.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) método


Añade una imagen a una presentación desde un objeto Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objeto de imagen Svg [ISvgImage](../../isvgimage/) |

### Valor devuelto

Imagen añadida.

## Ver también

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)