---
title: GetImages()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací objekty Thumbnail Image pro všechny snímky prezentace.
type: docs
weight: 417
url: /cs/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method

Vrací objekty Thumbnail Image pro všechny snímky prezentace.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |

### Návratová hodnota

Bitmap objekty.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method

Vrací objekty Thumbnail Bitmap pro zadané snímky prezentace.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |

### Návratová hodnota

Bitmap objekty.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

Vrací objekty Thumbnail Image pro všechny snímky prezentace s vlastním škálováním.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| scaleX | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy x. |
| scaleY | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy y. |

### Návratová hodnota

Bitmap objekty.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method

Vrací objekty Thumbnail Image pro zadané snímky prezentace s vlastním škálováním.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |
| scaleX | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy x. |
| scaleY | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy y. |

### Návratová hodnota

Bitmap objekty.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

Vrací objekty Thumbnail Image pro všechny snímky prezentace se zadanou velikostí.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost vytvářeného obrázku. |

### Návratová hodnota

Bitmap objekty.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method

Vrací objekty Thumbnail Image pro zadané snímky prezentace se zadanou velikostí.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost vytvářeného obrázku. |

### Návratová hodnota

Bitmap objekty.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImage](../../iimage/)
* Třída [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Třída [IPresentation](../)
* Třída [Size](../../../system.drawing/size/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)