---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है। यदि ISlideShowTransition::set_AdvanceAfterTime() मेथड को कॉल नहीं किया गया था तो यह मान उपयोग किया जाएगा। डिफ़ॉल्ट मान 1000 है।"
type: docs
weight: 79
url: /hi/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() मेथड


डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है। यदि [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) मेथड को कॉल नहीं किया गया था तो यह मान उपयोग किया जाएगा। डिफ़ॉल्ट मान 1000 है।

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## संबंधित देखें

* क्लास [GifOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)