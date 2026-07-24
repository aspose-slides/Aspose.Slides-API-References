---
title: GetImages()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation zurück.
type: docs
weight: 417
url: /de/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) Methode


Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderoptionen. |

### Rückgabewert

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) Methode


Gibt Thumbnail-Bitmap-Objekte für angegebene Folien einer Präsentation zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderoptionen. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |

### Rückgabewert

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) Methode


Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderoptionen. |
| scaleX | **float** | Der Wert, um den dieses Thumbnail in X-Richtung skaliert wird. |
| scaleY | **float** | Der Wert, um den dieses Thumbnail in Y-Richtung skaliert wird. |

### Rückgabewert

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) Methode


Gibt Thumbnail-Bildobjekte für angegebene Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderoptionen. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |
| scaleX | **float** | Der Wert, um den dieses Thumbnail in X-Richtung skaliert wird. |
| scaleY | **float** | Der Wert, um den dieses Thumbnail in Y-Richtung skaliert wird. |

### Rückgabewert

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) Methode


Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit angegebener Größe zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderoptionen. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Größe des zu erstellenden Bildes. |

### Rückgabewert

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) Methode


Gibt Thumbnail-Bildobjekte für angegebene Folien einer Präsentation mit angegebener Größe zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderoptionen. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Größe des zu erstellenden Bildes. |

### Rückgabewert

Bitmap objects.

## Siehe auch

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Klasse [IPresentation](../)
* Klasse [Size](../../../system.drawing/size/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)