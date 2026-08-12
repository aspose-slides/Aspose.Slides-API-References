---
title: get_AdvanceAfter()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह विशेषता निर्धारित करती है कि स्लाइडशो कुछ समय के बाद अगले स्लाइड पर जाएगा या नहीं। पढ़ें bool.
type: docs
weight: 105
url: /hi/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() विधि


यह विशेषता निर्धारित करती है कि स्लाइडशो कुछ समय के बाद अगले स्लाइड पर जाएगा या नहीं। पढ़ें **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// पहला स्लाइड ट्रांज़िशन प्राप्त करें
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// जांचें कि Advance Slide After फ़्लैग चेक किया गया है
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After समय मान प्राप्त करें
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## संबंधित देखें

* क्लास [SlideShowTransition](../)
* नामस्थान [Aspose::Slides::SlideShow](../../)
* लाइब्रेरी [Aspose.Slides](../../../)