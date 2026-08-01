---
title: GetImages()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie.
type: docs
weight: 417
url: /nl/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) methode

Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |

### Retourwaarde

Bitmap-objecten.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) methode

Retourneert Thumbnail Bitmap-objecten voor opgegeven dia's van een presentatie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |

### Retourwaarde

Bitmap-objecten.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) methode

Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met aangepaste schaal.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| scaleX | **float** | De waarde waarmee deze Thumbnail in de x-richting wordt geschaald. |
| scaleY | **float** | De waarde waarmee deze Thumbnail in de y-richting wordt geschaald. |

### Retourwaarde

Bitmap-objecten.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) methode

Retourneert Thumbnail Image-objecten voor opgegeven dia's van een presentatie met aangepaste schaal.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |
| scaleX | **float** | De waarde waarmee deze Thumbnail in de x-richting wordt geschaald. |
| scaleY | **float** | De waarde waarmee deze Thumbnail in de y-richting wordt geschaald. |

### Retourwaarde

Bitmap-objecten.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) methode

Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met opgegeven grootte.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de te maken afbeelding. |

### Retourwaarde

Bitmap-objecten.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) methode

Retourneert Thumbnail Image-objecten voor opgegeven dia's van een presentatie met opgegeven grootte.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de te maken afbeelding. |

### Retourwaarde

Bitmap-objecten.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)