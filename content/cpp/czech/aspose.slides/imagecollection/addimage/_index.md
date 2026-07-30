---
title: AddImage()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá kopii obrázku z jiné prezentace.
type: docs
weight: 53
url: /cs/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metoda


Přidá kopii obrázku z jiné prezentace.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Source image. |

### Návratová hodnota

Přidaný obrázek.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) metoda


Přidá obrázek do prezentace.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Image to add. |

### Návratová hodnota

Přidaný obrázek.
## Poznámky


Tato metoda převádí metafily WMF/EMF na rastrový PNG obrázek před vložením do prezentace.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metoda


Přidá obrázek do prezentace ze streamu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Stream to add image from. |

### Návratová hodnota

Přidaný obrázek.
## Poznámky


Tato metoda může přidávat metafily WMF/EMF do prezentace bez převodu na rastrový PNG obrázek.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metoda


Přidá obrázek do prezentace ze streamu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add image from. |

### Návratová hodnota

Přidaný obrázek.
## Poznámky


Tato metoda může přidávat metafily WMF/EMF do prezentace bez převodu na rastrový PNG obrázek.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda


Vytvoří a přidá obrázek do prezentace ze streamu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add image file from. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | The behavior which will be applied to the stream. |

### Návratová hodnota

Přidáno [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metoda


Přidá obrázek do prezentace ze specifikovaného bufferu.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Návratová hodnota

Přidaný obrázek.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metoda


Přidá obrázek do prezentace ze objektu Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg image object [ISvgImage](../../isvgimage/) |

### Návratová hodnota

Přidaný obrázek.

## Viz také

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IPPImage](../../ippimage/)
* Třída [ImageCollection](../)
* Třída [IImage](../../iimage/)
* Třída [MemoryStream](../../../system.io/memorystream/)
* Třída [Stream](../../../system.io/stream/)
* Třída [ISvgImage](../../isvgimage/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)