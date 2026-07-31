---
title: set_TrimFromEnd()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Tulis float.
type: docs
weight: 443
url: /id/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) metode


Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Menulis **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setel waktu pemangkasan akhir menjadi 2 detik
audioFrame->set_TrimFromEnd(2000.0f);
```

## Lihat Juga

* Kelas [IAudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)