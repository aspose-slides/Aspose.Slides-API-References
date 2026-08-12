---
title: set_Sound()
second_title: Aspose.Slides for C++ API संदर्भ
description: हाइपरलिंक की चल रही आवाज़ का प्रतिनिधित्व करता है। IAudio लिखें।
type: docs
weight: 196
url: /hi/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) विधि


हाइपरलिंक की चल रही आवाज़ को दर्शाता है। लिखें [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले shape का हाइपरलिंक प्राप्त करें
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // हाइपरलिंक की ध्वनि को बाइट एरे में निकालें
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudio](../../iaudio/)
* क्लास [IHyperlink](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)