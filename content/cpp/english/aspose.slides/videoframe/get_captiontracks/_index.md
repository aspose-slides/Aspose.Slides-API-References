---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API Reference
description: Returns the closed captions collection of the video. Read-only ICaptionsCollection.
type: docs
weight: 261
url: /aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() method


Returns the closed captions collection of the video. Read-only [ICaptionsCollection](../../icaptionscollection/).

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"video with captions.pptx");

for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    System::SharedPtr<IVideoFrame> videoFrame = System::AsCast<IVideoFrame>(shape);
    if (videoFrame != nullptr)
    {
        continue;
    }

    for (auto&& captionTrack : videoFrame->get_CaptionTracks())
    {
        // Extracts the captions binary data and saves them to the file
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [VideoFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)