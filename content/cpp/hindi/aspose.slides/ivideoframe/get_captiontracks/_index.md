---
title: get_CaptionTracks()
second_title: Aspose.Slides के लिए C++ API रेफरेंस
description: ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह गुण केवल-पढ़ने-योग्य है और सभी कैप्शन ट्रैक सम्मिलित करने वाला एक ICaptionsCollection लौटाता है।
type: docs
weight: 261
url: /hi/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() विधि

ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह गुण केवल-पढ़ने-योग्य है और सभी कैप्शन ट्रैक शामिल करने वाला एक [ICaptionsCollection](../../icaptionscollection/) लौटाता है।

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## टिप्पणी

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
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [IVideoFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)