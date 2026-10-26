---
title: GetImages()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca obiekty Image dla wszystkich slajdów prezentacji.
type: docs
weight: 456
url: /pl/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metoda


Zwraca obiekty Image dla wszystkich slajdów prezentacji.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje Tiff. |

### Wartość zwracana

Obiekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metoda


Zwraca obiekty Thumbnail Image dla wybranych slajdów prezentacji.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, zaczynając od 1. |

### Wartość zwracana

Obiekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda


Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji z niestandardowym skalowaniem.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje Tiff. |
| scaleX | **float** | Wartość, o którą skalować ten Thumbnail w kierunku osi x. |
| scaleY | **float** | Wartość, o którą skalować ten Thumbnail w kierunku osi y. |

### Wartość zwracana

Obiekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metoda


Zwraca obiekty Thumbnail Image dla wybranych slajdów prezentacji z niestandardowym skalowaniem.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, zaczynając od 1. |
| scaleX | **float** | Wartość, o którą skalować ten Thumbnail w kierunku osi x. |
| scaleY | **float** | Wartość, o którą skalować ten Thumbnail w kierunku osi y. |

### Wartość zwracana

Obiekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda


Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji o określonym rozmiarze.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekty Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metoda


Zwraca obiekty Thumbnail Image dla wybranych slajdów prezentacji o określonym rozmiarze.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, zaczynając od 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekty Image.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IImage](../../iimage/)
* Klasa [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Klasa [Presentation](../)
* Klasa [Size](../../../system.drawing/size/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)