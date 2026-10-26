---
title: AddImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een afbeelding toe vanuit een andere presentatie.
type: docs
weight: 53
url: /nl/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) methode


Voegt een kopie van een afbeelding toe vanuit een andere presentatie.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Bronafbeelding. |

### Retourwaarde

Toegevoegde afbeelding.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) methode


Voeg een afbeelding toe aan een presentatie.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Afbeelding om toe te voegen. |

### Retourwaarde

Toegevoegde afbeelding.

## Opmerkingen


Deze methode converteert WMF/EMF-metabestanden naar een raster PNG-afbeelding voordat ze aan een presentatie worden toegevoegd.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) methode


Voeg een afbeelding toe aan een presentatie vanuit een stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Stream waaruit de afbeelding wordt toegevoegd. |

### Retourwaarde

Toegevoegde afbeelding.

## Opmerkingen


Deze methode kan WMF/EMF-metabestanden aan een presentatie toevoegen zonder ze te converteren naar een raster PNG-afbeelding.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) methode


Voeg een afbeelding toe aan een presentatie vanuit een stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream waaruit de afbeelding wordt toegevoegd. |

### Retourwaarde

Toegevoegde afbeelding.

## Opmerkingen


Deze methode kan WMF/EMF-metabestanden aan een presentatie toevoegen zonder ze te converteren naar een raster PNG-afbeelding.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) methode


Maakt en voegt een afbeelding toe aan een presentatie vanuit een stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream waaruit het afbeeldingsbestand wordt toegevoegd. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Het gedrag dat op de stream zal worden toegepast. |

### Retourwaarde

Toegevoegde [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) methode


Voegt een afbeelding toe aan een presentatie vanuit een opgegeven buffer.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Retourwaarde

Toegevoegde afbeelding.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) methode


Voeg een afbeelding toe aan een presentatie vanuit een Svg-object.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg-afbeeldingsobject [ISvgImage](../../isvgimage/) |

### Retourwaarde

Toegevoegde afbeelding.

## Zie ook

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)