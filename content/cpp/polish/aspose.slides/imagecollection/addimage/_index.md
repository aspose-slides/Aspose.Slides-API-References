---
title: AddImage()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Dodaje kopię obrazu z innej prezentacji.
type: docs
weight: 53
url: /pl/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metoda


Dodaje kopię obrazu z innej prezentacji.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Źródłowy obraz. |

### Wartość zwracana

Dodany obraz.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) metoda


Dodaje obraz do prezentacji.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Obraz do dodania. |

### Wartość zwracana

Dodany obraz.

## Uwagi


Ta metoda konwertuje metafile WMF/EMF na rastrowy obraz PNG przed wstawieniem do prezentacji.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metoda


Dodaje obraz do prezentacji ze strumienia.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Strumień, z którego ma być dodany obraz. |

### Wartość zwracana

Dodany obraz.

## Uwagi


Ta metoda może dodać metafile WMF/EMF do prezentacji bez konwertowania ich na rastrowy obraz PNG.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metoda


Dodaje obraz do prezentacji ze strumienia.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego ma być dodany obraz. |

### Wartość zwracana

Dodany obraz.

## Uwagi


Ta metoda może dodać metafile WMF/EMF do prezentacji bez konwertowania ich na rastrowy obraz PNG.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda


Tworzy i dodaje obraz do prezentacji ze strumienia.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego ma być dodany plik obrazu. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Zachowanie, które zostanie zastosowane do strumienia. |

### Wartość zwracana

Dodano [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metoda


Dodaje obraz do prezentacji z określonego bufora.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor. |

### Wartość zwracana

Dodany obraz.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metoda


Dodaje obraz do prezentacji z obiektu Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Obiekt obrazu Svg [ISvgImage](../../isvgimage/) |

### Wartość zwracana

Dodany obraz.

## Zobacz także

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