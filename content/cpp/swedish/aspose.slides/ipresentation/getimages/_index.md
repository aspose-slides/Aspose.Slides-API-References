---
title: GetImages()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar Thumbnail Image-objekt för alla bildspel i en presentation.
type: docs
weight: 417
url: /sv/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method

Returnerar Thumbnail Image-objekt för alla bildspel i en presentation.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |

### Returvärde

Bitmap-objekt.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method

Returnerar Thumbnail Bitmap-objekt för angivna bildspel i en presentation.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildspelspositioner, med början på 1. |

### Returvärde

Bitmap-objekt.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

Returnerar Thumbnail Image-objekt för alla bildspel i en presentation med anpassad skalning.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| scaleX | **float** | Värdet som används för att skala denna miniatyr i x-axelns riktning. |
| scaleY | **float** | Värdet som används för att skala denna miniatyr i y-axelns riktning. |

### Returvärde

Bitmap-objekt.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method

Returnerar Thumbnail Image-objekt för angivna bildspel i en presentation med anpassad skalning.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildspelspositioner, med början på 1. |
| scaleX | **float** | Värdet som används för att skala denna miniatyr i x-axelns riktning. |
| scaleY | **float** | Värdet som används för att skala denna miniatyr i y-axelns riktning. |

### Returvärde

Bitmap-objekt.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

Returnerar Thumbnail Image-objekt för alla bildspel i en presentation med angiven storlek.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storlek på bilden som ska skapas. |

### Returvärde

Bitmap-objekt.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method

Returnerar Thumbnail Image-objekt för angivna bildspel i en presentation med angiven storlek.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array med bildspelspositioner, med början på 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storlek på bilden som ska skapas. |

### Returvärde

Bitmap-objekt.

## Se även

* Typdef [ArrayPtr](../../../system/arrayptr/)
* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [IImage](../../iimage/)
* Klass [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Klass [IPresentation](../)
* Klass [Size](../../../system.drawing/size/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)