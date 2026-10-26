---
title: AddImage()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá obrázek do prezentace.
type: docs
weight: 14
url: /cs/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) method

Přidejte obrázek do prezentace.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Obrázek k přidání. |

### Návratová hodnota

Přidaný obrázek.

## Poznámky

Tato metoda převádí metafily WMF/EMF na rastrový PNG obrázek před vložením do prezentace.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) method

Přidá obrázek z paměťového proudu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Paměťový proud. |

### Návratová hodnota

Přidaný obrázek.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) method

Přidejte obrázek do prezentace z proudu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud, ze kterého se má obrázek přidat. |

### Návratová hodnota

Přidaný obrázek.

## Poznámky

Tato metoda může přidat metafily WMF/EMF do prezentace bez jejich převodu na rastrový PNG obrázek.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

Vytvoří a přidá obrázek do prezentace z proudu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud, ze kterého se má soubor obrázku přidat. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Chování, které bude aplikováno na proud. |

### Návratová hodnota

Přidaný [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) method

Přidá obrázek do prezentace ze zadaného bufferu.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Návratová hodnota

Přidaný obrázek.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) method

Přidá kopii obrázku z jiné prezentace.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Zdrojový obrázek. |

### Návratová hodnota

Přidaný obrázek.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) method

Přidejte obrázek do prezentace z objektu SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objekt SVG obrázku [ISvgImage](../../isvgimage/) |

### Návratová hodnota

Přidaný obrázek.

## Viz také

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IPPImage](../../ippimage/)
* Třída [IImage](../../iimage/)
* Třída [IImageCollection](../)
* Třída [MemoryStream](../../../system.io/memorystream/)
* Třída [Stream](../../../system.io/stream/)
* Třída [ISvgImage](../../isvgimage/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)