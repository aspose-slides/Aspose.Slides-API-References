---
title: GetImage()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett bildobjekt med anpassad skalning.
type: docs
weight: 105
url: /sv/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) method

Returnerar ett bildobjekt med anpassad skalning.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | **float** | Värdet som används för att skala den här Thumbnail i x-axelns riktning. |
| scaleY | **float** | Värdet som används för att skala den här Thumbnail i y-axelns riktning. |

### Returvärde

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() method

Returnerar ett miniatyr-Image-objekt (20 % av verklig storlek).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Returvärde

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) method

Returnerar ett bildobjekt med angiven storlek.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på bilden som ska skapas. |

### Returvärde

Bitmap-objekt.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) method

Returnerar ett miniatyr-tiff-bitmap-objekt med angivna parametrar.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff-alternativ. |

### Returvärde

Image object.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) method

Returnerar ett miniatyr-Bitmap-objekt.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |

### Returvärde

Bitmap-objekt.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

Returnerar ett miniatyr-Bitmap-objekt med anpassad skalning.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| scaleX | **float** | Värdet som används för att skala den här Thumbnail i x-axelns riktning. |
| scaleY | **float** | Värdet som används för att skala den här Thumbnail i y-axelns riktning. |

### Returvärde

Bitmap-objekt.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

Returnerar ett miniatyr-Bitmap-objekt med angiven storlek.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på bilden som ska skapas. |

### Returvärde

Bitmap-objekt.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImage](../../iimage/)
* Klass [ISlide](../)
* Klass [Size](../../../system.drawing/size/)
* Klass [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Klass [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)