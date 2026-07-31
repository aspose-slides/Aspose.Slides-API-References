---
title: get_VolumeValue()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan volume audio dalam persentase. Baca float.
type: docs
weight: 378
url: /id/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() metode


Mengembalikan volume audio dalam persen. Baca **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Bingkai Audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Atur durasi fade awal selama 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)