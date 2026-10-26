---
title: set_TrimFromStart()
second_title: Aspose.Slides для C++ API Reference
description: Начало обрезки [мс]
type: docs
weight: 222
url: /ru/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) метод


Начало обрезки [мс]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Примечания


Пример: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//установить время начала обрезки 1 сек
videoFrame->set_TrimFromStart(1000.0f);

//установить время окончания обрезки 2 сек
videoFrame->set_TrimFromEnd(2000.0f);
```

## См. также

* Класс [VideoFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)