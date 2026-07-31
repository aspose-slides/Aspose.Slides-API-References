---
title: InsertAudioFrameEmbedded()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membuat bingkai audio baru dengan file WAV tersemat dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Audio tersemat ditambahkan ke koleksi Presentation::get_Audios."
type: docs
weight: 300
url: /id/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metode


Membuat sebuah bingkai audio baru dengan file WAV tersemat dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Audio tersemat ditambahkan ke koleksi [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bingkai audio. |
| x | **float** | Koordinat x dari bingkai audio baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai audio baru, dalam poin. |
| width | **float** | Lebar bingkai audio baru, dalam poin. |
| height | **float** | Tinggi bingkai audio baru, dalam poin. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran masukan yang berisi data audio WAV untuk disematkan. |

### Nilai Kembali

[IAudioFrame](../../iaudioframe/) yang baru dibuat.

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metode


Membuat bingkai audio baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bingkai audio. |
| x | **float** | Koordinat x dari bingkai audio baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai audio baru, dalam poin. |
| width | **float** | Lebar bingkai audio baru, dalam poin. |
| height | **float** | Tinggi bingkai audio baru, dalam poin. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Sebuah instance [IAudio](../../iaudio/) dari koleksi [Presentation::get_Audios](../../presentation/get_audios/) untuk disematkan. |

### Nilai Kembali

[IAudioFrame](../../iaudioframe/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudioFrame](../../iaudioframe/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [ShapeCollection](../)
* Kelas [IAudio](../../iaudio/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)