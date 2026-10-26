---
title: set_TrimFromStart()
second_title: Αναφορά API Aspose.Slides για C++
description: Αρχή περικοπής [ms]
type: docs
weight: 222
url: /el/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) μέθοδος

Αρχή περικοπής [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ορισμός χρόνου εκκίνησης περικοπής 1 δευτ
videoFrame->set_TrimFromStart(1000.0f);

//ορισμός χρόνου λήξης περικοπής 2 δευτ
videoFrame->set_TrimFromEnd(2000.0f);
```

## Δείτε επίσης

* Κλάση [IVideoFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)