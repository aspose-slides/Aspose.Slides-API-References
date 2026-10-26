---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API referencia
description: A vágás kezdete [ms]
type: docs
weight: 222
url: /hu/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) method


A vágás kezdete [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## Megjegyzések


Példa: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//állítsa be a vágás kezdő időpontját 1 másodpercre
videoFrame->set_TrimFromStart(1000.0f);

//állítsa be a vágás befejező időpontját 2 másodpercre
videoFrame->set_TrimFromEnd(2000.0f);
```

## Lásd még

* Osztály [IVideoFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)