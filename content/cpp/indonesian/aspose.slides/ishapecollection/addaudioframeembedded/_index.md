---
title: AddAudioFrameEmbedded()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah audio frame baru dengan file WAV yang disematkan dan menambahkannya ke akhir koleksi shape. Audio yang disematkan ditambahkan ke koleksi Presentation.Audios.
type: docs
weight: 248
url: /id/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method

Membuat sebuah audio frame baru dengan file WAV yang disematkan dan menambahkannya ke akhir koleksi shape. Audio yang disematkan ditambahkan ke koleksi Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Koordinat x dari audio frame baru, dalam poin. |
| y | **float** | Koordinat y dari audio frame baru, dalam poin. |
| width | **float** | Lebar audio frame baru, dalam poin. |
| height | **float** | Tinggi audio frame baru, dalam poin. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran input yang berisi data audio WAV untuk disematkan. |

### Nilai Kembali

Objek [IAudioFrame](../../iaudioframe/) yang baru dibuat.

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method

Membuat sebuah audio frame baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang sudah ada dari daftar Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Koordinat x dari audio frame baru, dalam poin. |
| y | **float** | Koordinat y dari audio frame baru, dalam poin. |
| width | **float** | Lebar audio frame baru, dalam poin. |
| height | **float** | Tinggi audio frame baru, dalam poin. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Sebuah instance [IAudio](../../iaudio/) dari koleksi Presentation.Audios. |

### Nilai Kembali

Objek [IAudioFrame](../../iaudioframe/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudioFrame](../../iaudioframe/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [IShapeCollection](../)
* Kelas [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)