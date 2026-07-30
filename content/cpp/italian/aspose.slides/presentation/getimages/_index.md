---
title: GetImages()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce oggetti Image per tutte le diapositive di una presentazione.
type: docs
weight: 456
url: /it/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metodo


Restituisce oggetti Image per tutte le diapositive di una presentazione.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni Tiff. |

### Valore di ritorno

Oggetti Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metodo


Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array con le posizioni delle diapositive, a partire da 1. |

### Valore di ritorno

Oggetti Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metodo


Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con ridimensionamento personalizzato.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni Tiff. |
| scaleX | **float** | Il valore di scala per questa Miniatura lungo l'asse x. |
| scaleY | **float** | Il valore di scala per questa Miniatura lungo l'asse y. |

### Valore di ritorno

Oggetti Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metodo


Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con ridimensionamento personalizzato.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array con le posizioni delle diapositive, a partire da 1. |
| scaleX | **float** | Il valore di scala per questa Miniatura lungo l'asse x. |
| scaleY | **float** | Il valore di scala per questa Miniatura lungo l'asse y. |

### Valore di ritorno

Oggetti Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metodo


Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con dimensione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Dimensione dell'immagine da creare. |

### Valore di ritorno

Oggetti Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metodo


Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con dimensione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array con le posizioni delle diapositive, a partire da 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Dimensione dell'immagine da creare. |

### Valore di ritorno

Oggetti Image.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Classe [Presentation](../)
* Classe [Size](../../../system.drawing/size/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)