---
title: GetImages()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt ein Image-Objekt für alle Folien einer Präsentation zurück.
type: docs
weight: 456
url: /de/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) Methode

Gibt ein Image-Objekt für alle Folien einer Präsentation zurück.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-Optionen. |

### Rückgabewert

Image-Objekte.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) Methode

Gibt ein Thumbnail Image-Objekt für die angegebenen Folien einer Präsentation zurück.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-Optionen. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |

### Rückgabewert

Image-Objekte.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) Methode

Gibt ein Thumbnail Image-Objekt für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-Optionen. |
| scaleX | **float** | Der Wert, um den dieses Thumbnail in x-Achsen-Richtung skaliert wird. |
| scaleY | **float** | Der Wert, um den dieses Thumbnail in y-Achsen-Richtung skaliert wird. |

### Rückgabewert

Image-Objekte.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) Methode

Gibt ein Thumbnail Image-Objekt für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-Optionen. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |
| scaleX | **float** | Der Wert, um den dieses Thumbnail in x-Achsen-Richtung skaliert wird. |
| scaleY | **float** | Der Wert, um den dieses Thumbnail in y-Achsen-Richtung skaliert wird. |

### Rückgabewert

Image-Objekte.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) Methode

Gibt ein Thumbnail Image-Objekt für alle Folien einer Präsentation mit angegebener Größe zurück.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-Optionen. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Größe des zu erstellenden Bildes. |

### Rückgabewert

Image-Objekte.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) Methode

Gibt ein Thumbnail Image-Objekt für die angegebenen Folien einer Präsentation mit angegebener Größe zurück.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff-Optionen. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Größe des zu erstellenden Bildes. |

### Rückgabewert

Image-Objekte.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Klasse [Presentation](../)
* Klasse [Size](../../../system.drawing/size/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)