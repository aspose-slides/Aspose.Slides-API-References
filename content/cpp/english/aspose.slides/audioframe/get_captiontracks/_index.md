---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API Reference
description: Gets the collection of closed captions associated with the audio frame. This property is read-only and returns an ICaptionsCollection containing all caption tracks.
type: docs
weight: 456
url: /aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() method


Gets the collection of closed captions associated with the audio frame. This property is read-only and returns an [ICaptionsCollection](../../icaptionscollection/) containing all caption tracks.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Save the caption track's binary data as a .vtt file
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)