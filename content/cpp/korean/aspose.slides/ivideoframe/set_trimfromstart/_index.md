---
title: set_TrimFromStart()
second_title: Aspose.Slides C++ API 참조
description: 시작 트림 [ms]
type: docs
weight: 222
url: /ko/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) 메서드


시작 트림 [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## 비고


예시: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//시작 트리밍 시간을 1초로 설정
videoFrame->set_TrimFromStart(1000.0f);

//끝 트리밍 시간을 2초로 설정
videoFrame->set_TrimFromEnd(2000.0f);
```

## 참고

* 클래스 [IVideoFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)