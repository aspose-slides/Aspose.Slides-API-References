---
title: set_TransitionFps()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ट्रांज़िशन FPS [frames/sec] सेट करता है। डिफ़ॉल्ट मान 25 है।
type: docs
weight: 66
url: /hi/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) मेथड


ट्रांज़िशन FPS [frames/sec] सेट करता है। डिफ़ॉल्ट मान 25 है।

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## देखें

* क्लास [GifOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)