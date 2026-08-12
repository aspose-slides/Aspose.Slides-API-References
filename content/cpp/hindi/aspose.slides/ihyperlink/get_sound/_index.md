---
title: get_Sound()
second_title: Aspose.Slides for C++ API संदर्भ
description: हाइपरलिंक की बजती ध्वनि का प्रतिनिधित्व करता है। पढ़ें IAudio।
type: docs
weight: 183
url: /hi/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() विधि


हाइपरलिंक की बजती ध्वनि को दर्शाता है। पढ़ें [IAudio](../../iaudio/)।

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले आकार का हाइपरलिंक प्राप्त करें
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // हाइपरलिंक की ध्वनि को बाइट एरे में निकालें
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudio](../../iaudio/)
* क्लास [IHyperlink](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)