---
title: AddImage()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Dodaj obraz do prezentacji.
type: docs
weight: 14
url: /pl/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) metoda


Dodaj obraz do prezentacji.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Obraz do dodania. |

### Wartość zwracana

Dodany obraz.
## Uwagi


Ta metoda konwertuje metafile WMF/EMF na rastrowy obraz PNG przed wstawieniem do prezentacji.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metoda


Dodaje obraz ze strumienia pamięci.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Strumień pamięci. |

### Wartość zwracana

Dodany obraz.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metoda


Dodaje obraz do prezentacji ze strumienia.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego dodać obraz. |

### Wartość zwracana

Dodany obraz.
## Uwagi


Ta metoda może dodać metafile WMF/EMF do prezentacji bez konwertowania ich na rastrowy obraz PNG.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda


Tworzy i dodaje obraz do prezentacji ze strumienia.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego dodać plik obrazu. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Zachowanie, które zostanie zastosowane do strumienia. |

### Wartość zwracana

Dodany [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metoda


Dodaje obraz do prezentacji z określonego bufora.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor. |

### Wartość zwracana

Dodany obraz.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metoda


Dodaje kopię obrazu z innej prezentacji.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obraz źródłowy. |

### Wartość zwracana

Dodany obraz.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metoda


Dodaje obraz do prezentacji z obiektu SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Obiekt obrazu SVG [ISvgImage](../../isvgimage/) |

### Wartość zwracana

Dodany obraz.

## Zobacz także

* Wyliczenie [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)