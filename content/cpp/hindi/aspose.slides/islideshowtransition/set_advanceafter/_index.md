---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह विशेषता निर्धारित करता है कि स्लाइडशो एक निश्चित समय के बाद अगले स्लाइड पर जाएगा। लिखें bool.
type: docs
weight: 118
url: /hi/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) विधि

यह विशेषता निर्धारित करती है कि स्लाइडशो एक निश्चित समय के बाद अगले स्लाइड पर जाएगा। लिखें **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// पहले स्लाइड ट्रांज़िशन प्राप्त करें
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// जाँचें कि Advance Slide After फ़्लैग सेट है
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After समय मान प्राप्त करें
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## संबंधित देखें

* क्लास [ISlideShowTransition](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)