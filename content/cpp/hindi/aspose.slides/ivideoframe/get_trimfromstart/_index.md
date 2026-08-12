---
title: get_TrimFromStart()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ट्रिम आरम्भ [ms]
type: docs
weight: 209
url: /hi/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() विधि


ट्रिम आरम्भ [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ट्रिमिंग शुरू समय 1सेक सेट करें
videoFrame->set_TrimFromStart(1000.0f);

//ट्रिमिंग समाप्त समय 2सेक सेट करें
videoFrame->set_TrimFromEnd(2000.0f);
```

## देखें

* क्लास [IVideoFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)