---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिफ़ॉल्ट देरी समय [ms] सेट करता है। यह मान तब उपयोग किया जाएगा जब ISlideShowTransition::set_AdvanceAfterTime() विधि को कॉल नहीं किया गया हो। डिफ़ॉल्ट मान 1000 है।"
type: docs
weight: 92
url: /hi/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) विधि


डिफ़ॉल्ट देरी समय [ms] सेट करता है। यह मान तब उपयोग किया जाएगा जब [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) विधि को कॉल नहीं किया गया हो। डिफ़ॉल्ट मान 1000 है।

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## देखें

* क्लास [GifOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)