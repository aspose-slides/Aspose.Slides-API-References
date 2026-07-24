---
title: AddImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu.
type: docs
weight: 53
url: /de/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) Methode


Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Quellbild. |

### Rückgabewert

Hinzugefügtes Bild.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) Methode


Fügt ein Bild zu einer Präsentation hinzu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Bild, das hinzugefügt werden soll. |

### Rückgabewert

Hinzugefügtes Bild.

## Hinweise


Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild, bevor sie in eine Präsentation eingefügt wird.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) Methode


Fügt ein Bild aus einem Stream zu einer Präsentation hinzu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Stream, aus dem das Bild hinzugefügt werden soll. |

### Rückgabewert

Hinzugefügtes Bild.

## Hinweise


Diese Methode kann WMF/EMF-Metadateien zu einer Präsentation hinzufügen, ohne sie in ein Raster-PNG-Bild zu konvertieren.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) Methode


Fügt ein Bild aus einem Stream zu einer Präsentation hinzu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem das Bild hinzugefügt werden soll. |

### Rückgabewert

Hinzugefügtes Bild.

## Hinweise


Diese Methode kann WMF/EMF-Metadateien zu einer Präsentation hinzufügen, ohne sie in ein Raster-PNG-Bild zu konvertieren.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) Methode


Erstellt und fügt ein Bild aus einem Stream zu einer Präsentation hinzu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem die Bilddatei hinzugefügt wird. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Das Verhalten, das auf den Stream angewendet wird. |

### Rückgabewert

Hinzugefügtes [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) Methode


Fügt ein Bild aus einem angegebenen Puffer zu einer Präsentation hinzu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Puffer. |

### Rückgabewert

Hinzugefügtes Bild.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) Methode


Fügt ein Bild aus einem SVG-Objekt zu einer Präsentation hinzu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg-Bildobjekt [ISvgImage](../../isvgimage/) |

### Rückgabewert

Hinzugefügtes Bild.

## Siehe auch

* Aufzählung [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [ImageCollection](../)
* Klasse [IImage](../../iimage/)
* Klasse [MemoryStream](../../../system.io/memorystream/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ISvgImage](../../isvgimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)