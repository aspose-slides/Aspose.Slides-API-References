---
title: GetImage()
second_title: Aspose.Slides dla C++ – dokumentacja API
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
| scaleX | **float** | Wartość, o którą skalujemy tę miniaturę w kierunku osi x. |
| scaleY | **float** | Wartość, o którą skalujemy tę miniaturę w kierunku osi y. |

### Wartość zwracana

Obiekt Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() metoda

Zwraca obiekt obrazu miniatury (20% rzeczywistego rozmiaru).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Wartość zwracana

Obiekt Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

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

Obiekt Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metoda

Zwraca obiekt bitmapy TIFF miniatury z określonymi parametrami.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opcje TIFF. |

### Wartość zwracana

Obiekt Image.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metoda

Zwraca obiekt bitmapy miniatury.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |

### Wartość zwracana

Obiekty Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda

Zwraca obiekt bitmapy miniatury z niestandardowym skalowaniem.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| scaleX | **float** | Wartość, o którą skalujemy tę miniaturę w kierunku osi x. |
| scaleY | **float** | Wartość, o którą skalujemy tę miniaturę w kierunku osi y. |

### Wartość zwracana

Obiekty Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda

Zwraca obiekt bitmapy miniatury o określonym rozmiarze.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekty Bitmap.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)