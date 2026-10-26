---
title: set_TrimFromStart()
second_title: Referensi API Aspose.Slides untuk C++
description: Awal pemotongan [ms]
type: docs
weight: 222
url: /id/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) metode

Awal pemotongan [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Catatan

Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//atur pemotongan awal 1 detik
videoFrame->set_TrimFromStart(1000.0f);

//atur pemotongan akhir 2 detik
videoFrame->set_TrimFromEnd(2000.0f);
```

## Lihat Juga

* Kelas [VideoFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)