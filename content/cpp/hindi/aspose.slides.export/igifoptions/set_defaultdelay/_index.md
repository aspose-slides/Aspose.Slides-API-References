---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिफ़ॉल्ट विलंब समय [ms] सेट करता है। यदि ISlideShowTransition::set_AdvanceAfterTime() मेथड को कॉल नहीं किया गया तो यह मान उपयोग किया जाएगा। डिफ़ॉल्ट मान 1000 है।"
type: docs
weight: 92
url: /hi/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) मेथड

डिफ़ॉल्ट विलंब समय [ms] सेट करता है। यदि [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) मेथड को कॉल नहीं किया गया तो यह मान उपयोग किया जाएगा। डिफ़ॉल्ट मान 1000 है।

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## देखें

* क्लास [IGifOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)