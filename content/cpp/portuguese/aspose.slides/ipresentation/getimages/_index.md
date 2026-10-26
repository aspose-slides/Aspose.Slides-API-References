---
title: GetImages()
second_title: Referência da API Aspose.Slides para C++
description: Retorna objetos Thumbnail Image para todos os slides de uma apresentação.
type: docs
weight: 417
url: /pt/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method


Retorna objetos **Thumbnail Image** para todos os slides de uma apresentação.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |

### Valor de Retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method


Retorna objetos **Thumbnail Bitmap** para slides específicos de uma apresentação.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array com posições dos slides, começando em 1. |

### Valor de Retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


Retorna objetos **Thumbnail Image** para todos os slides de uma apresentação com escala personalizada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| scaleX | **float** | O valor pelo qual dimensionar esta miniatura na direção do eixo x. |
| scaleY | **float** | O valor pelo qual dimensionar esta miniatura na direção do eixo y. |

### Valor de Retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method


Retorna objetos **Thumbnail Image** para slides específicos de uma apresentação com escala personalizada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array com posições dos slides, começando em 1. |
| scaleX | **float** | O valor pelo qual dimensionar esta miniatura na direção do eixo x. |
| scaleY | **float** | O valor pelo qual dimensionar esta miniatura na direção do eixo y. |

### Valor de Retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


Retorna objetos **Thumbnail Image** para todos os slides de uma apresentação com tamanho especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamanho da imagem a ser criada. |

### Valor de Retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method


Retorna objetos **Thumbnail Image** para slides específicos de uma apresentação com tamanho especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array com posições dos slides, começando em 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamanho da imagem a ser criada. |

### Valor de Retorno

Objetos Bitmap.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)