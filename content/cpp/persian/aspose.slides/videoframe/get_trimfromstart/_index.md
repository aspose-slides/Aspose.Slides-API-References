---
title: get_TrimFromStart()
second_title: Aspose.Slides برای C++ مرجع API
description: زمان شروع برش [ms]
type: docs
weight: 209
url: /fa/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() متد


زمان شروع برش [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## توضیحات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//تنظیم زمان شروع برش 1 ثانیه
videoFrame->set_TrimFromStart(1000.0f);

//تنظیم زمان پایان برش 2 ثانیه
videoFrame->set_TrimFromEnd(2000.0f);
```

## موارد مرتبط

* کلاس [VideoFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)