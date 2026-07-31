---
title: AddAudioFrameEmbedded()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membuat frame audio baru dengan file WAV yang disematkan dan menambahkannya ke akhir koleksi shape. Audio yang disematkan ditambahkan ke koleksi Presentation::get_Audios."
type: docs
weight: 287
url: /id/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metode

Membuat frame audio baru dengan file WAV yang disematkan dan menambahkannya ke akhir koleksi shape. Audio yang disematkan ditambahkan ke koleksi [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame audio baru, dalam point. |
| y | **float** | Koordinat y dari frame audio baru, dalam point. |
| width | **float** | Lebar frame audio baru, dalam point. |
| height | **float** | Tinggi frame audio baru, dalam point. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran masukan yang berisi data audio WAV untuk disematkan. |

### Nilai Kembalian

[IAudioFrame](../../iaudioframe/) yang baru dibuat.

## Catatan

Contoh berikut menunjukkan cara membuat Frame [Audio](../../audio/).
```cpp
// Membuat instance kelas presentasi yang mewakili file presentasi
auto pres = System::MakeObject<Presentation>();

// Mendapatkan slide pertama
auto slide = pres->get_Slides()->idx_get(0);
// Memuat file suara wav ke stream
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Menambahkan Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Mengatur Mode Putar dan Volume Audio
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Menulis file PowerPoint ke disk
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) metode

Membuat frame audio baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang sudah ada dari daftar [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame audio baru, dalam point. |
| y | **float** | Koordinat y dari frame audio baru, dalam point. |
| width | **float** | Lebar frame audio baru, dalam point. |
| height | **float** | Tinggi frame audio baru, dalam point. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Sebuah instance [IAudio](../../iaudio/) dari koleksi [Presentation::get_Audios](../../presentation/get_audios/). |

### Nilai Kembalian

[IAudioFrame](../../iaudioframe/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudioFrame](../../iaudioframe/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [ShapeCollection](../)
* Kelas [IAudio](../../iaudio/)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)