---
title: AddAudio()
second_title: Aspose.Slides for C++ API Referansı
description: Başka bir sunumdan bir ses dosyasının kopyasını ekler.
type: docs
weight: 53
url: /tr/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) yöntem

Başka bir sunumdan bir ses dosyasının kopyasını ekler.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Kaynak ses. |

### Dönüş Değeri

Eklenen ses.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) yöntem

Bir akıştan bir ses oluşturur ve bir sunuma ekler.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ses eklemek için akış. |

### Dönüş Değeri

Eklenen ses.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) yöntemi


Bir akıştan bir ses oluşturur ve bir sunuma ekler.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Video sesinin ekleneceği akış. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Akışa uygulanacak davranış. |

### Dönüş Değeri

Eklenen ses.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) yöntemi


Bir bayt dizisinden bir ses oluşturur ve bir sunuma ekler.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bayt. |

### Dönüş Değeri

Eklenen ses.

## Ayrıca Bakınız

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)