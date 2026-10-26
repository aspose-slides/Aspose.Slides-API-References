---
title: AddImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Bild zu einer Präsentation hinzu.
type: docs
weight: 14
url: /de/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) Methode

Fügt ein Bild zu einer Präsentation hinzu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Bild, das hinzugefügt werden soll. |

### Rückgabewert

Hinzugefügtes Bild.

## Bemerkungen

Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild, bevor sie zu einer Präsentation eingefügt wird.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) Methode

Fügt ein Bild aus einem Memory-Stream hinzu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Speicher-Stream. |

### Rückgabewert

Hinzugefügtes Bild.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) Methode

Fügt ein Bild zu einer Präsentation aus einem Stream hinzu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem das Bild hinzugefügt wird. |

### Rückgabewert

Hinzugefügtes Bild.

## Bemerkungen

Diese Methode kann WMF/EMF-Metadateien zu einer Präsentation hinzufügen, ohne sie in ein Raster-PNG-Bild zu konvertieren.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) Methode

Erstellt und fügt ein Bild zu einer Präsentation aus einem Stream hinzu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem die Bilddatei hinzugefügt wird. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Das Verhalten, das auf den Stream angewendet wird. |

### Rückgabewert

Hinzugefügt [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) Methode

Fügt ein Bild zu einer Präsentation aus einem angegebenen Puffer hinzu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Puffer. |

### Rückgabewert

Hinzugefügtes Bild.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) Methode

Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Quellbild. |

### Rückgabewert

Hinzugefügtes Bild.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) Methode

Fügt ein Bild zu einer Präsentation aus einem SVG-Objekt hinzu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG-Bildobjekt [ISvgImage](../../isvgimage/) |

### Rückgabewert

Hinzugefügtes Bild.

## Siehe auch

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)