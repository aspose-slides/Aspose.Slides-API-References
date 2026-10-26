---
title: AddImage()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma imagem a uma apresentação.
type: docs
weight: 14
url: /pt/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) método


Adiciona uma imagem a uma apresentação.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Imagem a ser adicionada. |

### Valor de Retorno

Imagem adicionada.

## Observações


Este método converte arquivos metafile WMF/EMF em imagem PNG raster antes de inseri-los em uma apresentação.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) método


Adiciona imagem a partir de um fluxo de memória.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Fluxo de memória. |

### Valor de Retorno

Imagem adicionada.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) método


Adiciona uma imagem a uma apresentação a partir de um fluxo.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de onde a imagem será adicionada. |

### Valor de Retorno

Imagem adicionada.

## Observações


Este método pode adicionar arquivos metafile WMF/EMF a uma apresentação sem convertê-los em imagem PNG raster.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método


Cria e adiciona uma imagem a uma apresentação a partir de um fluxo.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de onde o arquivo de imagem será adicionado. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | O comportamento que será aplicado ao fluxo. |

### Valor de Retorno

Adicionado [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) método


Adiciona uma imagem a uma apresentação a partir do buffer especificado.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Valor de Retorno

Imagem adicionada.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) método


Adiciona uma cópia de uma imagem de outra apresentação.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Imagem de origem. |

### Valor de Retorno

Imagem adicionada.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) método


Adiciona uma imagem a uma apresentação a partir de um objeto SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objeto de imagem SVG [ISvgImage](../../isvgimage/) |

### Valor de Retorno

Imagem adicionada.

## Veja Também

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