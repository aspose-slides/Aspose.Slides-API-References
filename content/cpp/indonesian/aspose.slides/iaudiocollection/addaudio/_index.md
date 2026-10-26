---
title: AddAudio()
second_title: Aspose.Slides untuk Referensi API C++
description: Menambahkan salinan file audio dari presentasi lain.
type: docs
weight: 14
url: /id/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) method

Menambahkan salinan file audio dari presentasi lain.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Audio sumber. |

### Nilai Kembalian

Audio yang ditambahkan.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) method

Membuat dan menambahkan audio ke presentasi dari stream.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream untuk menambahkan audio dari. |

### Nilai Kembalian

Audio yang ditambahkan.

Usang
:   Gunakan AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Metode ini akan dihapus pada versi 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

Membuat dan menambahkan audio ke presentasi dari stream.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream untuk menambahkan audio video dari. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Perilaku yang akan diterapkan pada stream. |

### Nilai Kembalian

Audio yang ditambahkan.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) method

Membuat dan menambahkan audio ke presentasi dari array byte.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) byte. |

### Nilai Kembalian

Audio yang ditambahkan.

## Lihat Juga

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IAudio](../../iaudio/)
* Kelas [IAudioCollection](../)
* Kelas [Stream](../../../system.io/stream/)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)