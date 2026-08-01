---
title: GetImages()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een Image-object voor alle dia's van een presentatie.
type: docs
weight: 456
url: /nl/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) methode


Retourneert een Image-object voor alle dia's van een presentatie.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-opties. |

### Retourwaarde

Image-objecten.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) methode


Retourneert een Thumbnail Image-object voor opgegeven dia's van een presentatie.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-opties. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |

### Retourwaarde

Image-objecten.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) methode


Retourneert een Thumbnail Image-object voor alle dia's van een presentatie met aangepaste scaling.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-opties. |
| scaleX | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scaleY | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

### Retourwaarde

Image-objecten.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) methode


Retourneert een Thumbnail Image-object voor opgegeven dia's van een presentatie met aangepaste scaling.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-opties. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |
| scaleX | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scaleY | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

### Retourwaarde

Image-objecten.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) methode


Retourneert een Thumbnail Image-object voor alle dia's van een presentatie met opgegeven grootte.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-opties. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de te maken afbeelding. |

### Retourwaarde

Image-objecten.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) methode


Retourneert een Thumbnail Image-object voor opgegeven dia's van een presentatie met opgegeven grootte.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-opties. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de te maken afbeelding. |

### Retourwaarde

Image-objecten.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Klasse [Presentation](../)
* Klasse [Size](../../../system.drawing/size/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)