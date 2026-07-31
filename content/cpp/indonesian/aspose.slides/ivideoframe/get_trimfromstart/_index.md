---
title: get_TrimFromStart()
second_title: Referensi API Aspose.Slides untuk C++
description: Awal pemangkasan [ms]
type: docs
weight: 209
url: /id/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() metode

Awal pemangkasan [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## Catatan

Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//atur waktu pemangkasan awal 1 detik
videoFrame->set_TrimFromStart(1000.0f);

//atur waktu pemangkasan akhir 2 detik
videoFrame->set_TrimFromEnd(2000.0f);
```

## Lihat Juga

* Kelas [IVideoFrame](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)