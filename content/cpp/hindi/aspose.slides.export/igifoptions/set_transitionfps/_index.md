---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API संदर्भ
description: ट्रांज़िशन FPS [frames/sec] सेट करता है। डिफ़ॉल्ट मान 25 है।
type: docs
weight: 66
url: /hi/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) विधि

ट्रांज़िशन FPS [frames/sec] सेट करता है। डिफ़ॉल्ट मान 25 है।

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## देखें भी

* क्लास [IGifOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)