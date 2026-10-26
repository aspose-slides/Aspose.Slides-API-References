---
title: AddImage()
second_title: Aspose.Slides için C++ API Referansı
description: Sunuma bir resim ekler.
type: docs
weight: 14
url: /tr/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) method

Sunuma bir resim ekler.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Eklenilecek resim. |

### Dönüş Değeri

Eklenen resim.

## Notlar

Bu yöntem, WMF/EMF meta dosyalarını bir sunuma eklemeden önce raster PNG görüntüsüne dönüştürür.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) method

Bellek akışından bir resmi ekler.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Bellek akışı. |

### Dönüş Değeri

Eklenen resim.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) method

Akıştan bir resmi sunuma ekler.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Resmin ekleneceği akış. |

### Dönüş Değeri

Eklenen resim.

## Notlar

Bu yöntem, WMF/EMF meta dosyalarını raster PNG görüntüsüne dönüştürmeden bir sunuma ekleyebilir.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

Akıştan bir resmi oluşturur ve sunuma ekler.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Resim dosyasının ekleneceği akış. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Akışa uygulanacak davranış. |

### Dönüş Değeri

Eklenen [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) method

Belirtilen tampondan bir resmi sunuma ekler.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tampon. |

### Dönüş Değeri

Eklenen resim.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) method

Başka bir sunumdan bir resmin kopyasını ekler.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Kaynak resim. |

### Dönüş Değeri

Eklenen resim.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) method

SVG nesnesinden bir resmi sunuma ekler.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG resim nesnesi [ISvgImage](../../isvgimage/) |

### Dönüş Değeri

Eklenen resim.

## Ayrıca Bakınız

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