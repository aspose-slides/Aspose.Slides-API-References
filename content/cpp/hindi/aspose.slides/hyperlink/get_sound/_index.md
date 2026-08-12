---
title: get_Sound()
second_title: Aspose.Slides for C++ API संदर्भ
description: हाइपरलिंक की चल रही ध्वनि को दर्शाता है। पढ़ें IAudio.
type: docs
weight: 287
url: /hi/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() विधि


हाइपरलिंक की चल रही ध्वनि को दर्शाता है। पढ़ें [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## टिप्पणियाँ



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

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudio](../../iaudio/)
* क्लास [Hyperlink](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)