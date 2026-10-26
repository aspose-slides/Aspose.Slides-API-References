---
title: AddAudio()
second_title: Aspose.Slides için C++ API Referansı
description: Başka bir sunumdan bir ses dosyasının kopyasını ekler.
type: docs
weight: 14
url: /tr/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metodu

Başka bir sunumdan bir ses dosyasının kopyasını ekler.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Kaynak ses. |

### Dönüş Değeri

Eklenen ses.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metodu

Akıştan bir sunuma ses oluşturur ve ekler.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ses eklenecek akış. |

### Dönüş Değeri

Eklenen ses.

Kullanımdan Kaldırıldı
:   Kullanın AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Metod 17.10 sürümünde kaldırılacak.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metodu

Akıştan bir sunuma ses oluşturur ve ekler.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Video sesinin ekleneceği akış. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Akışa uygulanacak davranış. |

### Dönüş Değeri

Eklenen ses.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metodu

Bayt dizisinden bir sunuma ses oluşturur ve ekler.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bayt. |

### Dönüş Değeri

Eklenen ses.

## İlgili

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)