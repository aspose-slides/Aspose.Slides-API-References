---
title: AddImage()
second_title: Aspose.Slides for C++ API Referansı
description: Başka bir sunumdan bir görüntünün kopyasını ekler.
type: docs
weight: 53
url: /tr/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metot


Başka bir sunumdan bir görüntünün kopyasını ekler.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Kaynak görüntü. |

### Dönüş Değeri

Eklenen görüntü.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) metot


Bir sunuma görüntü ekler.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Eklenecek görüntü. |

### Dönüş Değeri

Eklenen görüntü.
## Açıklamalar


Bu metot, WMF/EMF metafilelerini bir sunuma eklemeden önce raster PNG görüntüsüne dönüştürür.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metot


Akıştan bir sunuma görüntü ekler.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Görüntünün ekleneceği akış. |

### Dönüş Değeri

Eklenen görüntü.
## Açıklamalar


Bu metot, WMF/EMF metafilelerini raster PNG görüntüsüne dönüştürmeden bir sunuma ekleyebilir.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metot


Akıştan bir sunuma görüntü ekler.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Görüntünün ekleneceği akış. |

### Dönüş Değeri

Eklenen görüntü.
## Açıklamalar


Bu metot, WMF/EMF metafilelerini raster PNG görüntüsüne dönüştürmeden bir sunuma ekleyebilir.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metot


Akıştan bir sunuma görüntü oluşturur ve ekler.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Görüntü dosyasının ekleneceği akış. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Akışa uygulanacak davranış. |

### Dönüş Değeri

Eklenen [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metot


Belirtilen tampon üzerinden bir sunuma görüntü ekler.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tampon. |

### Dönüş Değeri

Eklenen görüntü.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metot


Svg nesnesinden bir sunuma görüntü ekler.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg görüntü nesnesi [ISvgImage](../../isvgimage/) |

### Dönüş Değeri

Eklenen görüntü.

## Ayrıca Bakınız

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