---
title: get_TrimFromStart()
second_title: Aspose.Slides για C++ API Reference
description: Αποκοπή έναρξης [ms]
type: docs
weight: 209
url: /el/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() μέθοδος


Αποκοπή έναρξης [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ορίστε το χρόνο έναρξης αποκοπής 1 δευτερόλεπτο
videoFrame->set_TrimFromStart(1000.0f);

//ορίστε το χρόνο λήξης αποκοπής 2 δευτερόλεπτα
videoFrame->set_TrimFromEnd(2000.0f);
```

## Δείτε επίσης

* Κλάση [IVideoFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)