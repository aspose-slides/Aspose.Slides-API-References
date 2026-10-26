---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑडियो फ़्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने योग्य है और एक ICaptionsCollection लौटाता है जिसमें सभी कैप्शन ट्रैक्स शामिल हैं।
type: docs
weight: 456
url: /hi/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() विधि


ऑडियो फ़्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने योग्य है और एक [ICaptionsCollection](../../icaptionscollection/) लौटाता है जिसमें सभी कैप्शन ट्रैक्स शामिल हैं।

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // कैप्शन ट्रैक का बाइनरी डेटा .vtt फाइल के रूप में सहेजें
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## और देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)