---
title: AddImage()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en bild i en presentation.
type: docs
weight: 14
url: /sv/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) metod


Lägg till en bild i en presentation.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Bild att lägga till. |

### Returvärde

Tillagd bild.

## Anmärkningar


Denna metod konverterar WMF/EMF-metafiler till raster-PNG-bild innan den infogas i en presentation.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metod


Lägger till en bild från en minnesström.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Minnesström. |

### Returvärde

Tillagd bild.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metod


Lägg till en bild i en presentation från ström.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till bild från. |

### Returvärde

Tillagd bild.

## Anmärkningar


Denna metod kan lägga till WMF/EMF-metafiler i en presentation utan att konvertera dem till raster-PNG-bild.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metod


Skapar och lägger till en bild i en presentation från ström.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till bildfil från. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Beteendet som kommer att tillämpas på strömmen. |

### Returvärde

Tillagd [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metod


Lägger till en bild i en presentation från en specificerad buffer.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Returvärde

Tillagd bild.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metod


Lägger till en kopia av en bild från en annan presentation.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Källbild. |

### Returvärde

Tillagd bild.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metod


Lägg till en bild i en presentation från SVG-objekt.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG-bildobjekt [ISvgImage](../../isvgimage/) |

### Returvärde

Tillagd bild.

## Se också

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IPPImage](../../ippimage/)
* Klass [IImage](../../iimage/)
* Klass [IImageCollection](../)
* Klass [MemoryStream](../../../system.io/memorystream/)
* Klass [Stream](../../../system.io/stream/)
* Klass [ISvgImage](../../isvgimage/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)