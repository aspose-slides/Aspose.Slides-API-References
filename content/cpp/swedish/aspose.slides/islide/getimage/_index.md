---
title: GetImage()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett bildobjekt med anpassad skalning.
type: docs
weight: 105
url: /sv/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) metod


Returnerar ett bildobjekt med anpassad skalning.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | **float** | Värdet med vilket detta miniatyrbild ska skalas i x-axelns riktning. |
| scaleY | **float** | Värdet med vilket detta miniatyrbild ska skalas i y-axelns riktning. |

### Returvärde

Image object [IImage](../../iimage/)

## ISlide::GetImage() metod


Returnerar ett miniatyrbildsobjekt (20 % av verklig storlek).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Returvärde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) metod


Returnerar ett bildobjekt med angiven storlek.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på bilden som ska skapas. |

### Returvärde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metod


Returnerar ett miniatur-tiff-bitmapobjekt med angivna parametrar.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff-alternativ. |

### Returvärde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metod


Returnerar ett miniatur-bitmap-objekt.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |

### Returvärde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metod


Returnerar ett miniatur-bitmap-objekt med anpassad skalning.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| scaleX | **float** | Värdet med vilket detta miniatyrbild ska skalas i x-axelns riktning. |
| scaleY | **float** | Värdet med vilket detta miniatyrbild ska skalas i y-axelns riktning. |

### Returvärde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metod


Returnerar ett miniatur-bitmap-objekt med angiven storlek.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på bilden som ska skapas. |

### Returvärde

Image object [IImage](../../iimage/)

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImage](../../iimage/)
* Klass [ISlide](../)
* Klass [Size](../../../system.drawing/size/)
* Klass [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Klass [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)