---
title: set_Sound()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: हाइपरलिंक की चल रही ध्वनि का प्रतिनिधित्व करता है। IAudio लिखें।
type: docs
weight: 300
url: /hi/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) मेथड


हाइपरलिंक की चल रही ध्वनि का प्रतिनिधित्व करता है। [IAudio](../../iaudio/) लिखें।

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले आकार के हाइपरलिंक को प्राप्त करें
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // हाइपरलिंक की ध्वनि को बाइट ऐरे में निकालें
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudio](../../iaudio/)
* क्लास [Hyperlink](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)