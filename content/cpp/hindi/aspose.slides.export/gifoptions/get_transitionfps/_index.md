---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API संदर्भ
description: ट्रांज़िशन FPS [frames/sec] प्राप्त करता है। डिफ़ॉल्ट मान 25 है।
type: docs
weight: 53
url: /hi/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() विधि


ट्रांज़िशन FPS [frames/sec] प्राप्त करता है। डिफ़ॉल्ट मान 25 है।

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## संबंधित देखें

* क्लास [GifOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)