---
title: get_TrimFromStart()
second_title: Aspose.Slides C++ API 레퍼런스
description: 시작 트림 [ms]
type: docs
weight: 209
url: /ko/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() 메서드

시작 트림 [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## 비고

예제: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//시작 트림 시간을 1초로 설정
videoFrame->set_TrimFromStart(1000.0f);

//끝 트림 시간을 2초로 설정
videoFrame->set_TrimFromEnd(2000.0f);
```

## 참조

* 클래스 [VideoFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)