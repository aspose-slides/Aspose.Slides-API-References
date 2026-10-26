---
title: set_TrimFromStart()
second_title: Aspose.Slides C++ API Referansı
description: Kesme başlangıcı [ms]
type: docs
weight: 222
url: /tr/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) metodu


Kesme başlangıcı [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//başlangıç kesme süresini 1 saniye ayarla
videoFrame->set_TrimFromStart(1000.0f);

//bitiş kesme süresini 2 saniye ayarla
videoFrame->set_TrimFromEnd(2000.0f);
```

## Ayrıca Bakınız

* Sınıf [IVideoFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)