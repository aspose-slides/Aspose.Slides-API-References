---
title: get_CaptionTracks()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऑडियो फ्रेम से जुड़ी बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने-योग्य है और सभी कैप्शन ट्रैक्स को शामिल करने वाला एक ICaptionsCollection लौटाती है।
type: docs
weight: 456
url: /hi/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() विधि

ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने-योग्य है और सभी कैप्शन ट्रैक्स को शामिल करने वाला एक [ICaptionsCollection](../../icaptionscollection/) लौटाता है।

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // कैप्शन ट्रैक की बाइनरी डेटा को .vtt फ़ाइल के रूप में सहेजें
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ICaptionsCollection](../../icaptionscollection/)
* क्लास [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)