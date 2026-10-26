---
title: get_TrimFromStart()
second_title: Aspose.Slides C++ API referencia
description: Kezdeti vágás [ms]
type: docs
weight: 209
url: /hu/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() metódus


Kezdeti vágás [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## Megjegyzések


Példa: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//állítsa be a vágás kezdő időt 1 másodperc
videoFrame->set_TrimFromStart(1000.0f);

//állítsa be a vágás befejezési időt 2 másodperc
videoFrame->set_TrimFromEnd(2000.0f);
```

## Lásd még

* Osztály [IVideoFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)