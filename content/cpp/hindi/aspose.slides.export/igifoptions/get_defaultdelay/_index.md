---
title: get_DefaultDelay()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "डिफ़ॉल्ट विलंब समय [ms] प्राप्त करता है। यदि ISlideShowTransition::set_AdvanceAfterTime() विधि को कॉल नहीं किया गया तो यह मान उपयोग किया जाएगा। डिफ़ॉल्ट मान 1000 है।"
type: docs
weight: 79
url: /hi/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() विधि

डिफ़ॉल्ट विलंब समय [ms] प्राप्त करता है। यदि [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) विधि को कॉल नहीं किया गया तो यह मान उपयोग किया जाएगा। डिफ़ॉल्ट मान 1000 है।

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## संबंधित देखें

* वर्ग [IGifOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)