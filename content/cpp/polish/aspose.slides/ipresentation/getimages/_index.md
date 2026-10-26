---
title: GetImages()
second_title: Referencja API Aspose.Slides dla C++
description: Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji.
type: docs
weight: 417
url: /pl/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metoda

Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |

### Wartość zwracana

Obiekty Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metoda

Zwraca obiekty Thumbnail Bitmap dla określonych slajdów prezentacji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, począwszy od 1. |

### Wartość zwracana

Obiekty Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda

Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji z niestandardowym skalowaniem.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| scaleX | **float** | Wartość, o którą skalować tę Thumbnail w kierunku osi x. |
| scaleY | **float** | Wartość, o którą skalować tę Thumbnail w kierunku osi y. |

### Wartość zwracana

Obiekty Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metoda

Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji z niestandardowym skalowaniem.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, począwszy od 1. |
| scaleX | **float** | Wartość, o którą skalować tę Thumbnail w kierunku osi x. |
| scaleY | **float** | Wartość, o którą skalować tę Thumbnail w kierunku osi y. |

### Wartość zwracana

Obiekty Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda

Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji o określonym rozmiarze.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekty Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metoda

Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji o określonym rozmiarze.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, począwszy od 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekty Bitmap.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IImage](../../iimage/)
* Klasa [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Klasa [IPresentation](../)
* Klasa [Size](../../../system.drawing/size/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)