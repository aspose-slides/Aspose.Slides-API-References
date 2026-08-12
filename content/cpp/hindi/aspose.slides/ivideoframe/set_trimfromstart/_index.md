---
title: set_TrimFromStart()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: कटाव की शुरुआत [ms]
type: docs
weight: 222
url: /hi/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) विधि


कटाव की शुरुआत [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//कटाव की शुरुआत समय 1सेकंड
videoFrame->set_TrimFromStart(1000.0f);

//कटाव का अंत समय 2सेकंड
videoFrame->set_TrimFromEnd(2000.0f);
```

## संबंधित देखें

* क्लास [IVideoFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)