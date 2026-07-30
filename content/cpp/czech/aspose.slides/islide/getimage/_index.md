---
title: GetImage()
second_title: Aspose.Slides pro C++ referenci API
description: Vrací objekt Image s vlastním měřítkem.
type: docs
weight: 105
url: /cs/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) metoda


Vrací objekt Image s vlastním měřítkem.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| scaleX | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy x. |
| scaleY | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy y. |

### Návratová hodnota

Objekt Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() metoda


Vrací Thumbnail Image objekt (20% skutečné velikosti).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Návratová hodnota

Objekt Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) metoda


Vrací objekt Image se zadanou velikostí.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost obrázku, který se má vytvořit. |

### Návratová hodnota

Objekt Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metoda


Vrací Thumbnail tiff bitmap objekt se zadanými parametry.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Možnosti Tiff. |

### Návratová hodnota

Objekt Image.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metoda


Vrací Thumbnail Bitmap objekt.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |

### Návratová hodnota

Objekty Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda


Vrací Thumbnail Bitmap objekt s vlastním měřítkem.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| scaleX | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy x. |
| scaleY | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy y. |

### Návratová hodnota

Objekty Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda


Vrací Thumbnail Bitmap objekt se zadanou velikostí.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost obrázku, který se má vytvořit. |

### Návratová hodnota

Objekty Bitmap.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImage](../../iimage/)
* Třída [ISlide](../)
* Třída [Size](../../../system.drawing/size/)
* Třída [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Třída [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)