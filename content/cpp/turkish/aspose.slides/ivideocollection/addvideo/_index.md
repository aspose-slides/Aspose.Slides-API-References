---
title: AddVideo()
second_title: Aspose.Slides için C++ API Referansı
description: Başka bir sunumdan bir video dosyasının kopyasını ekler.
type: docs
weight: 14
url: /tr/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) yöntemi

Başka bir sunumdan bir video dosyasının kopyasını ekler.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Kaynak video. |

### Dönüş Değeri

Eklenen video.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) yöntemi

Akıştan bir sunuma video oluşturur ve ekler.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Video dosyasının ekleneceği akış. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Akışa uygulanacak davranış. |

### Dönüş Değeri

Eklenen [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) yöntemi

Bayt dizisinden bir sunuma video oluşturur ve ekler.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bayt. |

### Dönüş Değeri

Eklenen video.

## Ayrıca Bakınız

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [IVideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)