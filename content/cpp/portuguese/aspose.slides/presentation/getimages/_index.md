---
title: GetImages()
second_title: Aspose.Slides para C++ - Referência da API
description: Retorna objetos Image para todos os slides de uma apresentação.
type: docs
weight: 456
url: /pt/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) método


Retorna objetos Image para todos os slides de uma apresentação.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções Tiff. |

### Valor de Retorno

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) método


Retorna objetos Thumbnail Image para slides especificados de uma apresentação.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz com posições dos slides, começando em 1. |

### Valor de Retorno

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) método


Retorna objetos Thumbnail Image para todos os slides de uma apresentação com dimensionamento personalizado.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções Tiff. |
| scaleX | **float** | O valor pelo qual dimensionar esta Miniatura na direção do eixo x. |
| scaleY | **float** | O valor pelo qual dimensionar esta Miniatura na direção do eixo y. |

### Valor de Retorno

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) método


Retorna objetos Thumbnail Image para slides especificados de uma apresentação com dimensionamento personalizado.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz com posições dos slides, começando em 1. |
| scaleX | **float** | O valor pelo qual dimensionar esta Miniatura na direção do eixo x. |
| scaleY | **float** | O valor pelo qual dimensionar esta Miniatura na direção do eixo y. |

### Valor de Retorno

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) método


Retorna objetos Thumbnail Image para todos os slides de uma apresentação com tamanho especificado.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamanho da imagem a ser criada. |

### Valor de Retorno

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) método


Retorna objetos Thumbnail Image para slides especificados de uma apresentação com tamanho especificado.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz com posições dos slides, começando em 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamanho da imagem a ser criada. |

### Valor de Retorno

Objetos Image.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Classe [Presentation](../)
* Classe [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)