---
title: set_TrimFromStart()
second_title: Aspose.Slides C++ API referencia
description: Vágás kezdete [ms]
type: docs
weight: 222
url: /hu/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) metódus


Vágás kezdete [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Megjegyzések


Példa: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//állítsa be a vágás kezdési időt 1 másodperc
videoFrame->set_TrimFromStart(1000.0f);

//állítsa be a vágás befejezési időt 2 másodperc
videoFrame->set_TrimFromEnd(2000.0f);
```

## Lásd még

* Osztály [VideoFrame](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)