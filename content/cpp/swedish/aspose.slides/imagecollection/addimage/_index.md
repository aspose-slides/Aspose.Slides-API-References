---
title: AddImage()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en bild från en annan presentation.
type: docs
weight: 53
url: /sv/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metod

Adds a copy of an image from an another presentation.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Källbild. |

### Returvärde

Tillagd bild.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) metod

Add an image to a presentation.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Bild att lägga till. |

### Returvärde

Tillagd bild.

## Anmärkningar

Denna metod konverterar WMF/EMF-metadatafiler till raster-PNG-bild innan den infogas i en presentation.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metod

Add an image to a presentation from stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Ström att lägga till bild från. |

### Returvärde

Tillagd bild.

## Anmärkningar

Denna metod kan lägga till WMF/EMF-metadatafiler i en presentation utan att konvertera dem till raster-PNG-bild.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metod

Add an image to a presentation from stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till bild från. |

### Returvärde

Tillagd bild.

## Anmärkningar

Denna metod kan lägga till WMF/EMF-metadatafiler i en presentation utan att konvertera dem till raster-PNG-bild.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metod

Creates and adds an image to a presentation from stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till bildfil från. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Beteendet som kommer att tillämpas på strömmen. |

### Returvärde

Tillagd [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metod

Adds an image to a presentation from specified buffer.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffert. |

### Returvärde

Tillagd bild.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metod

Add an image to a presentation from Svg object.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg-bildobjekt [ISvgImage](../../isvgimage/) |

### Returvärde

Tillagd bild.

## Se även

* Enumeration [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [IPPImage](../../ippimage/)
* Klass [ImageCollection](../)
* Klass [IImage](../../iimage/)
* Klass [MemoryStream](../../../system.io/memorystream/)
* Klass [Stream](../../../system.io/stream/)
* Klass [ISvgImage](../../isvgimage/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)