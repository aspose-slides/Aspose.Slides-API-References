---
title: get_VolumeValue()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan volume audio dalam persen. Baca float.
type: docs
weight: 378
url: /id/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() metode


Mengembalikan volume audio dalam persen. Baca **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## Keterangan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Atur durasi fade awal selama 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [IAudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)