---
title: get_TrimFromStart()
second_title: Aspose.Slides for C++ API 參考
description: 修剪起始位置 [ms]
type: docs
weight: 209
url: /zh-hant/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() 方法

修剪起始位置 [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## 備註

範例:
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//set triming start time 1sec
videoFrame->set_TrimFromStart(1000.0f);

//set triming end time 2sec
videoFrame->set_TrimFromEnd(2000.0f);
```

## 另請參閱

* 類別 [VideoFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)