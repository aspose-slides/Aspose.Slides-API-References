---
title: GetImage()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um objeto Image com dimensionamento personalizado.
type: docs
weight: 105
url: /pt/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) método


Retorna um objeto Image com dimensionamento personalizado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scaleX | **float** | O valor pelo qual escalar este Thumbnail na direção do eixo x. |
| scaleY | **float** | O valor pelo qual escalar este Thumbnail na direção do eixo y. |

### Valor de Retorno

Image object [IImage](../../iimage/)

## ISlide::GetImage() método


Retorna um objeto Thumbnail Image (20% do tamanho real).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Valor de Retorno

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) método


Retorna um objeto Image com tamanho especificado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamanho da imagem a ser criada. |

### Valor de Retorno

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) método


Retorna um objeto Thumbnail tiff bitmap com parâmetros especificados.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opções Tiff. |

### Valor de Retorno

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) método


Retorna um objeto Thumbnail Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |

### Valor de Retorno

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) método


Retorna um objeto Thumbnail Bitmap com dimensionamento personalizado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| scaleX | **float** | O valor pelo qual escalar este Thumbnail na direção do eixo x. |
| scaleY | **float** | O valor pelo qual escalar este Thumbnail na direção do eixo y. |

### Valor de Retorno

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) método


Retorna um objeto Thumbnail Bitmap com tamanho especificado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamanho da imagem a ser criada. |

### Valor de Retorno

Image object [IImage](../../iimage/)

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [ISlide](../)
* Classe [Size](../../../system.drawing/size/)
* Classe [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)