---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API संदर्भ
description: ट्रिम प्रारंभ [ms]
type: docs
weight: 222
url: /hi/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) मेथड

ट्रिम प्रारंभ [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## टिप्पणी

उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//set triming start time 1sec
//ट्रिमिंग शुरू समय 1 सेकंड सेट करें

//set triming end time 2sec
//ट्रिमिंग अंत समय 2 सेकंड सेट करें
```

## देखें

* क्लास [VideoFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)