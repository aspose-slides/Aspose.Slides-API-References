---
title: GetImage()
second_title: Aspose.Slides dla C++ – Referencja API
description: Zwraca obiekt obrazu z niestandardowym skalowaniem.
type: docs
weight: 105
url: /pl/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) metoda


Zwraca obiekt obrazu z niestandardowym skalowaniem.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| scaleX | **float** | Wartość, o którą należy skalować ten Thumbnail w kierunku osi x. |
| scaleY | **float** | Wartość, o którą należy skalować ten Thumbnail w kierunku osi y. |

### Wartość zwracana

Image object [IImage](../../iimage/)

## ISlide::GetImage() metoda


Zwraca obiekt Thumbnail Image (20% rzeczywistego rozmiaru).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Wartość zwracana

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) metoda


Zwraca obiekt obrazu o określonym rozmiarze.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metoda


Zwraca obiekt Thumbnail tiff bitmap z określonymi parametrami.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opcje Tiff. |

### Wartość zwracana

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metoda


Zwraca obiekt Thumbnail Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |

### Wartość zwracana

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda


Zwraca obiekt Thumbnail Bitmap z niestandardowym skalowaniem.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| scaleX | **float** | Wartość, o którą należy skalować ten Thumbnail w kierunku osi x. |
| scaleY | **float** | Wartość, o którą należy skalować ten Thumbnail w kierunku osi y. |

### Wartość zwracana

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda


Zwraca obiekt Thumbnail Bitmap o określonym rozmiarze.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Image object [IImage](../../iimage/)

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IImage](../../iimage/)
* Klasa [ISlide](../)
* Klasa [Size](../../../system.drawing/size/)
* Klasa [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Klasa [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)