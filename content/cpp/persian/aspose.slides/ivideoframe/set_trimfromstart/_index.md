---
title: set_TrimFromStart()
second_title: مرجع API Aspose.Slides برای C++
description: شروع برش [ms]
type: docs
weight: 222
url: /fa/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) متد

شروع برش [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## ملاحظات

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

## همچنین ببینید

* کلاس [IVideoFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)