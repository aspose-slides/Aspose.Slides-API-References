---
title: GetImages()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací objekty Image pro všechny snímky prezentace.
type: docs
weight: 456
url: /cs/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metoda


Vrací objekty Image pro všechny snímky prezentace.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti Tiff. |

### Návratová hodnota

Objekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metoda


Vrací objekty Thumbnail Image pro určené snímky prezentace.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |

### Návratová hodnota

Objekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda


Vrací objekty Thumbnail Image pro všechny snímky prezentace s vlastním škálováním.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti Tiff. |
| scaleX | **float** | Hodnota, o kterou se má tento Thumbnail škálovat podél osy x. |
| scaleY | **float** | Hodnota, o kterou se má tento Thumbnail škálovat podél osy y. |

### Návratová hodnota

Objekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metoda


Vrací objekty Thumbnail Image pro určené snímky prezentace s vlastním škálováním.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |
| scaleX | **float** | Hodnota, o kterou se má tento Thumbnail škálovat podél osy x. |
| scaleY | **float** | Hodnota, o kterou se má tento Thumbnail škálovat podél osy y. |

### Návratová hodnota

Objekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda


Vrací objekty Thumbnail Image pro všechny snímky prezentace se zadanou velikostí.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost obrázku, který se má vytvořit. |

### Návratová hodnota

Objekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metoda


Vrací objekty Thumbnail Image pro určené snímky prezentace se zadanou velikostí.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost obrázku, který se má vytvořit. |

### Návratová hodnota

Objekty Image.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImage](../../iimage/)
* Třída [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Třída [Presentation](../)
* Třída [Size](../../../system.drawing/size/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)