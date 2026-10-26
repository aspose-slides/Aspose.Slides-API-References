---
title: get_AdvanceAfter()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह विशेषता निर्धारित करती है कि स्लाइडशो एक निश्चित समय के बाद अगली स्लाइड पर जाएगा या नहीं। पढ़ें bool.
type: docs
weight: 105
url: /hi/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() विधि


यह विशेषता निर्धारित करती है कि स्लाइडशो किसी निश्चित समय के बाद अगली स्लाइड पर चलेगा या नहीं। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// पहली स्लाइड ट्रांज़िशन प्राप्त करें
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// जाँचें कि Advance Slide After फ़्लैग चुना गया है या नहीं
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After समय मान प्राप्त करें
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## देखें

* क्लास [ISlideShowTransition](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)