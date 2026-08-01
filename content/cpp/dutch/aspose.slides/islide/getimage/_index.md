---
title: GetImage()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert een afbeeldingobject met aangepaste schaal.
type: docs
weight: 105
url: /nl/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) methode


Retourneert een afbeeldingobject met aangepaste schaal.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | **float** | De waarde waarmee deze miniatuur op de x-as wordt geschaald. |
| scaleY | **float** | De waarde waarmee deze miniatuur op de y-as wordt geschaald. |

### Retourwaarde

Afbeeldingsobject [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() methode


Retourneert een miniatuurafbeeldingsobject (20% van de echte grootte).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Retourwaarde

Afbeeldingsobject [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) methode


Retourneert een afbeeldingobject met opgegeven grootte.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de te maken afbeelding. |

### Retourwaarde

Bitmapobject.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) methode


Retourneert een miniatuur-TIFF-bitmapobject met opgegeven parameters.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff-opties. |

### Retourwaarde

Afbeeldingsobject.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) methode


Retourneert een miniatuur-bitmapobject.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |

### Retourwaarde

Bitmapobjecten.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) methode


Retourneert een miniatuur-bitmapobject met aangepaste schaal.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| scaleX | **float** | De waarde waarmee deze miniatuur op de x-as wordt geschaald. |
| scaleY | **float** | De waarde waarmee deze miniatuur op de y-as wordt geschaald. |

### Retourwaarde

Bitmapobjecten.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) methode


Retourneert een miniatuur-bitmapobject met opgegeven grootte.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de te maken afbeelding. |

### Retourwaarde

Bitmapobjecten.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [ISlide](../)
* Klasse [Size](../../../system.drawing/size/)
* Klasse [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Klasse [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)