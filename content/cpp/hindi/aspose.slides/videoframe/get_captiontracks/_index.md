---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API संदर्भ
description: वीडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह गुण केवल पढ़ने योग्य है और सभी कैप्शन ट्रैक्स को समेटे हुए एक ICaptionsCollection लौटाता है।
type: docs
weight: 261
url: /hi/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() मेथड


वीडियो फ़्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह गुण केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैक्स को समेटे हुए एक [ICaptionsCollection](../../icaptionscollection/) लौटाता है।

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## टिप्पणियाँ


उदाहरण: 
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
        // कैप्शन का बाइनरी डेटा निकालता है और उसे फ़ाइल में सहेजता है
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ICaptionsCollection](../../icaptionscollection/)
* क्लास [VideoFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)