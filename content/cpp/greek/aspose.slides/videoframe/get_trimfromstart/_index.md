---
title: get_TrimFromStart()
second_title: Αναφορά API του Aspose.Slides για C++
description: Περικοπή από την αρχή [ms]
type: docs
weight: 209
url: /el/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() μέθοδος

Περικοπή από την αρχή [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//set triming start time 1sec
videoFrame->set_TrimFromStart(1000.0f);

//set triming end time 2sec
videoFrame->set_TrimFromEnd(2000.0f);
```

## Δείτε επίσης

* Κλάση [VideoFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)