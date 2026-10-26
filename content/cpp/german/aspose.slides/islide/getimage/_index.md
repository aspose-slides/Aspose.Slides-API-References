---
title: GetImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Bildobjekt mit benutzerdefinierter Skalierung zurück.
type: docs
weight: 105
url: /de/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) Methode

Gibt ein Bildobjekt mit benutzerdefinierter Skalierung zurück.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | **float** | Der Wert, um den dieses Thumbnail in Richtung der x-Achse skaliert wird. |
| scaleY | **float** | Der Wert, um den dieses Thumbnail in Richtung der y-Achse skaliert wird. |

### Rückgabewert

Bildobjekt [IImage](../../iimage/)

## ISlide::GetImage() Methode

Gibt ein Thumbnail-Bildobjekt (20 % der Originalgröße) zurück.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Rückgabewert

Bildobjekt [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) Methode

Gibt ein Bildobjekt mit der angegebenen Größe zurück.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Größe des zu erstellenden Bildes. |

### Rückgabewert

Bildobjekt [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) Methode

Gibt ein Thumbnail-Tiff-Bitmap-Objekt mit den angegebenen Parametern zurück.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff-Optionen. |

### Rückgabewert

Bildobjekt [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) Methode

Gibt ein Thumbnail-Bitmap-Objekt zurück.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-Optionen. |

### Rückgabewert

Bildobjekt [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) Methode

Gibt ein Thumbnail-Bitmap-Objekt mit benutzerdefinierter Skalierung zurück.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-Optionen. |
| scaleX | **float** | Der Wert, um den dieses Thumbnail in Richtung der x-Achse skaliert wird. |
| scaleY | **float** | Der Wert, um den dieses Thumbnail in Richtung der y-Achse skaliert wird. |

### Rückgabewert

Bildobjekt [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) Methode

Gibt ein Thumbnail-Bitmap-Objekt mit der angegebenen Größe zurück.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-Optionen. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Größe des zu erstellenden Bildes. |

### Rückgabewert

Bildobjekt [IImage](../../iimage/)

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [ISlide](../)
* Klasse [Size](../../../system.drawing/size/)
* Klasse [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Klasse [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)