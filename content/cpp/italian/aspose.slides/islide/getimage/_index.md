---
title: GetImage()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un oggetto immagine con ridimensionamento personalizzato.
type: docs
weight: 105
url: /it/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) metodo


Restituisce un oggetto immagine con ridimensionamento personalizzato.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | **float** | Il valore con cui ridimensionare questo thumbnail sull'asse x. |
| scaleY | **float** | Il valore con cui ridimensionare questo thumbnail sull'asse y. |

### Valore di ritorno

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() metodo


Restituisce un oggetto Thumbnail Image (20% della dimensione reale).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Valore di ritorno

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) metodo


Restituisce un oggetto immagine con dimensioni specificate.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Dimensione dell'immagine da creare. |

### Valore di ritorno

Bitmap object.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metodo


Restituisce un oggetto bitmap tiff thumbnail con parametri specificati.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opzioni Tiff. |

### Valore di ritorno

Image object.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metodo


Restituisce un oggetto Bitmap thumbnail.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni di rendering. |

### Valore di ritorno

oggetti Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metodo


Restituisce un oggetto Bitmap thumbnail con ridimensionamento personalizzato.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni di rendering. |
| scaleX | **float** | Il valore con cui ridimensionare questo thumbnail sull'asse x. |
| scaleY | **float** | Il valore con cui ridimensionare questo thumbnail sull'asse y. |

### Valore di ritorno

oggetti Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metodo


Restituisce un oggetto Bitmap thumbnail con dimensioni specificate.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni di rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Dimensione dell'immagine da creare. |

### Valore di ritorno

oggetti Bitmap.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [ISlide](../)
* Classe [Size](../../../system.drawing/size/)
* Classe [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)