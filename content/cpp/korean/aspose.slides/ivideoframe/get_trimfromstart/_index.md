---
title: get_TrimFromStart()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 시작 트림 [ms]
type: docs
weight: 209
url: /ko/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() 메서드


시작 트림 [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## 비고


예: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//설정 트리밍 시작 시간 1초
videoFrame->set_TrimFromStart(1000.0f);

//설정 트리밍 종료 시간 2초
videoFrame->set_TrimFromEnd(2000.0f);
```

## 참조

* 클래스 [IVideoFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)