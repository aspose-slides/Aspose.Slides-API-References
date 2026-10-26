---
title: set_AdvanceAfter()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: यह गुण निर्धारित करता है कि स्लाइडशो कुछ समय के बाद अगले स्लाइड पर जाएगा या नहीं। लिखें bool.
type: docs
weight: 118
url: /hi/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) विधि


यह गुण निर्दिष्ट करता है कि स्लाइडशो कुछ समय के बाद अगले स्लाइड पर जाएगा या नहीं। लिखें **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// पहला स्लाइड ट्रांज़िशन प्राप्त करें
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// जाँचें कि Advance Slide After फ़्लैग चुना गया है या नहीं
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After Time मान प्राप्त करें
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## देखें

* क्लास [SlideShowTransition](../)
* नामस्थान [Aspose::Slides::SlideShow](../../)
* लाइब्रेरी [Aspose.Slides](../../../)