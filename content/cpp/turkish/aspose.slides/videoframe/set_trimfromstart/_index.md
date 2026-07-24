---
title: set_TrimFromStart()
second_title: Aspose.Slides için C++ API Referansı
description: Kesme başlangıcı [ms]
type: docs
weight: 222
url: /tr/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) metodu


Kesme başlangıcı [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Açıklamalar


Örnek: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//başlangıç kırpma süresi 1 saniye
videoFrame->set_TrimFromStart(1000.0f);

//bitiş kırpma süresi 2 saniye
videoFrame->set_TrimFromEnd(2000.0f);
```

## Ayrıca bakınız

* Sınıf [VideoFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)