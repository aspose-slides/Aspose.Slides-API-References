---
title: GetImages()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar Image-objekt för alla bilder i en presentation.
type: docs
weight: 456
url: /sv/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metod


Returnerar Image-objekt för alla bilder i en presentation.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-alternativ. |

### Returvärde

Image-objekt.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metod


Returnerar Thumbnail Image-objekt för angivna bilder i en presentation.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-alternativ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildpositioner, med början från 1. |

### Returvärde

Image-objekt.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metod


Returnerar Thumbnail Image-objekt för alla bilder i en presentation med anpassad skalning.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-alternativ. |
| scaleX | **float** | Värdet att skala detta Thumbnail i x-axelns riktning. |
| scaleY | **float** | Värdet att skala detta Thumbnail i y-axelns riktning. |

### Returvärde

Image-objekt.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metod


Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med anpassad skalning.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-alternativ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildpositioner, med början från 1. |
| scaleX | **float** | Värdet att skala detta Thumbnail i x-axelns riktning. |
| scaleY | **float** | Värdet att skala detta Thumbnail i y-axelns riktning. |

### Returvärde

Image-objekt.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metod


Returnerar Thumbnail Image-objekt för alla bilder i en presentation med angiven storlek.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-alternativ. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på den bild som ska skapas. |

### Returvärde

Image-objekt.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metod


Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med angiven storlek.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-alternativ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildpositioner, med början från 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på den bild som ska skapas. |

### Returvärde

Image-objekt.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImage](../../iimage/)
* Klass [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Klass [Presentation](../)
* Klass [Size](../../../system.drawing/size/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)