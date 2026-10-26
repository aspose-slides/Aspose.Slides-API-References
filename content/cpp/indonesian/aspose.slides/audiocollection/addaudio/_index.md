---
title: AddAudio()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan salinan file audio dari presentasi lain.
type: docs
weight: 53
url: /id/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metode

Menambahkan salinan file audio dari presentasi lain.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Audio sumber. |

### Nilai Kembali

Audio yang ditambahkan.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metode

Membuat dan menambahkan audio ke presentasi dari stream.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream untuk menambahkan audio. |

### Nilai Kembali

Audio yang ditambahkan.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metode

Membuat dan menambahkan audio ke presentasi dari stream.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream untuk menambahkan audio video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Perilaku yang akan diterapkan pada stream. |

### Nilai Kembali

Audio yang ditambahkan.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metode

Membuat dan menambahkan audio ke presentasi dari array byte.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) byte. |

### Nilai Kembali

Audio yang ditambahkan.

## Lihat Juga

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IAudio](../../iaudio/)
* Kelas [AudioCollection](../)
* Kelas [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)