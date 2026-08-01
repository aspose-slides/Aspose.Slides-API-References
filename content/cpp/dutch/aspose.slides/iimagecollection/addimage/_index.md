---
title: AddImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een afbeelding toe aan een presentatie.
type: docs
weight: 14
url: /nl/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) methode


Voeg een afbeelding toe aan een presentatie.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Afbeelding om toe te voegen. |

### Retourwaarde

Toegevoegde afbeelding.
## Opmerkingen


Deze methode converteert WMF/EMF-metabestanden naar een raster-PNG-afbeelding voordat deze in een presentatie wordt ingevoegd.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) methode


Voegt afbeelding toe vanuit een geheugenstroom.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Geheugenstroom. |

### Retourwaarde

Toegevoegde afbeelding.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) methode


Voeg een afbeelding toe aan een presentatie vanuit een stream.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream waaruit de afbeelding moet worden toegevoegd. |

### Retourwaarde

Toegevoegde afbeelding.
## Opmerkingen


Deze methode kan WMF/EMF-metabestanden aan een presentatie toevoegen zonder ze te converteren naar een raster-PNG-afbeelding.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) methode


Maakt een afbeelding aan en voegt deze toe aan een presentatie vanuit een stream.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream waaruit het afbeeldingsbestand moet worden toegevoegd. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Het gedrag dat op de stream zal worden toegepast. |

### Retourwaarde

Toegevoegde [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) methode


Voegt een afbeelding toe aan een presentatie vanuit een opgegeven buffer.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Retourwaarde

Toegevoegde afbeelding.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) methode


Voegt een kopie van een afbeelding toe vanuit een andere presentatie.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Bronafbeelding. |

### Retourwaarde

Toegevoegde afbeelding.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) methode


Voeg een afbeelding toe aan een presentatie vanuit een SVG-object.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG-afbeeldingsobject [ISvgImage](../../isvgimage/) |

### Retourwaarde

Toegevoegde afbeelding.

## Zie ook

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [IImage](../../iimage/)
* Klasse [IImageCollection](../)
* Klasse [MemoryStream](../../../system.io/memorystream/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ISvgImage](../../isvgimage/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)