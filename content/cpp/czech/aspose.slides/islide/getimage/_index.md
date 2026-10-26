---
title: GetImage()
second_title: Aspose.Slides pro C++ referenci API
description: Vrací objekt obrázku s vlastním měřítkem.
type: docs
weight: 105
url: /cs/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) metoda


Vrací objekt obrázku s vlastním měřítkem.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| scaleX | **float** | Hodnota, o kterou se má tato miniatura škálovat ve směru osy x. |
| scaleY | **float** | Hodnota, o kterou se má tato miniatura škálovat ve směru osy y. |

### Návratová hodnota

Image object [IImage](../../iimage/)

## ISlide::GetImage() metoda


Vrací objekt miniatury obrázku (20% skutečné velikosti).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Návratová hodnota

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) metoda


Vrací objekt obrázku se zadanou velikostí.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost obrázku, který se má vytvořit. |

### Návratová hodnota

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metoda


Vrací objekt miniatury TIFF bitmapy se zadanými parametry.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Možnosti TIFF. |

### Návratová hodnota

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metoda


Vrací objekt miniatury bitmapy.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |

### Návratová hodnota

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda


Vrací objekt miniatury bitmapy s vlastním měřítkem.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| scaleX | **float** | Hodnota, o kterou se má tato miniatura škálovat ve směru osy x. |
| scaleY | **float** | Hodnota, o kterou se má tato miniatura škálovat ve směru osy y. |

### Návratová hodnota

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda


Vrací objekt miniatury bitmapy se zadanou velikostí.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost obrázku, který se má vytvořit. |

### Návratová hodnota

Image object [IImage](../../iimage/)

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)