---
title: AddImage()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona uma cópia de uma imagem de outra apresentação.
type: docs
weight: 53
url: /pt/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) method


Adiciona uma cópia de uma imagem de outra apresentação.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Imagem de origem. |

### Valor de Retorno

Imagem adicionada.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) method


Adiciona uma imagem a uma apresentação.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Imagem a ser adicionada. |

### Valor de Retorno

Imagem adicionada.
## Observações


Este método converte arquivos metafile WMF/EMF em imagem raster PNG antes de inseri-los em uma apresentação.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) method


Adiciona uma imagem a uma apresentação a partir de um fluxo.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Fluxo de onde a imagem será adicionada. |

### Valor de Retorno

Imagem adicionada.
## Observações


Este método pode adicionar arquivos WMF/EMF a uma apresentação sem convertê-los em imagem raster PNG.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) method


Adiciona uma imagem a uma apresentação a partir de um fluxo.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de onde a imagem será adicionada. |

### Valor de Retorno

Imagem adicionada.
## Observações


Este método pode adicionar arquivos WMF/EMF a uma apresentação sem convertê-los em imagem raster PNG.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method


Cria e adiciona uma imagem a uma apresentação a partir de um fluxo.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de onde o arquivo de imagem será adicionado. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | O comportamento que será aplicado ao fluxo. |

### Valor de Retorno

Adicionado [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) method


Adiciona uma imagem a uma apresentação a partir de um buffer especificado.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Valor de Retorno

Imagem adicionada.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) method


Adiciona uma imagem a uma apresentação a partir de um objeto Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objeto de imagem Svg [ISvgImage](../../isvgimage/) |

### Valor de Retorno

Imagem adicionada.

## Veja Também

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [ImageCollection](../)
* Classe [IImage](../../iimage/)
* Classe [MemoryStream](../../../system.io/memorystream/)
* Classe [Stream](../../../system.io/stream/)
* Classe [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)