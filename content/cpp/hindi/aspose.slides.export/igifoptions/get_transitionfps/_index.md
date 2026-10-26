---
title: get_TransitionFps()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: ट्रांज़िशन FPS [frames/sec] प्राप्त करता है। डिफ़ॉल्ट मान 25 है।
type: docs
weight: 53
url: /hi/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() विधि

ट्रांज़िशन FPS [frames/sec] प्राप्त करता है। डिफ़ॉल्ट मान 25 है।

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## संबंधित देखें

* क्लास [IGifOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)