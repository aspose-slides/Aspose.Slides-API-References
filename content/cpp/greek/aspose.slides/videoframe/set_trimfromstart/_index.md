---
title: set_TrimFromStart()
second_title: Aspose.Slides για C++ Αναφορά API
description: Έναρξη περικοπής [ms]
type: docs
weight: 222
url: /el/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) μέθοδος


Έναρξη περικοπής [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ορισμός χρόνου έναρξης κοπής 1 δευτερόλεπτο
videoFrame->set_TrimFromStart(1000.0f);

//ορισμός χρόνου λήξης κοπής 2 δευτερόλεπτα
videoFrame->set_TrimFromEnd(2000.0f);
```

## Δείτε επίσης

* Κλάση [VideoFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)