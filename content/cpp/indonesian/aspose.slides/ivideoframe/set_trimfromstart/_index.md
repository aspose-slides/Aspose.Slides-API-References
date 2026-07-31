---
title: set_TrimFromStart()
second_title: Referensi API Aspose.Slides untuk C++
description: Pemangkasan awal [ms]
type: docs
weight: 222
url: /id/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) metode

Pemangkasan awal [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## Keterangan

Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//atur pemangkasan waktu mulai 1 detik
videoFrame->set_TrimFromStart(1000.0f);

//atur pemangkasan waktu akhir 2 detik
videoFrame->set_TrimFromEnd(2000.0f);
```


## Lihat Juga

* Kelas [IVideoFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)