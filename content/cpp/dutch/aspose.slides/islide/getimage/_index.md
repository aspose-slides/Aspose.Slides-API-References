---
title: GetImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een Image object met aangepaste schaal.
type: docs
weight: 105
url: /nl/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) methode


Retourneert een image object met aangepaste schaal.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scaleY | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

### Retourwaarde

Image object [IImage](../../iimage/)

## ISlide::GetImage() methode


Retourneert een Thumbnail Image object (20 % van de werkelijke grootte).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Retourwaarde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) methode


Retourneert een image object met de opgegeven grootte.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de image om te maken. |

### Retourwaarde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) methode


Retourneert een Thumbnail tiff bitmap object met de opgegeven parameters.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff-opties. |

### Retourwaarde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) methode


Retourneert een Thumbnail Bitmap object.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-opties. |

### Retourwaarde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) methode


Retourneert een Thumbnail Bitmap object met aangepaste schaal.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-opties. |
| scaleX | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scaleY | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

### Retourwaarde

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) methode


Retourneert een Thumbnail Bitmap object met de opgegeven grootte.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-opties. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de image om te maken. |

### Retourwaarde

Image object [IImage](../../iimage/)

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)