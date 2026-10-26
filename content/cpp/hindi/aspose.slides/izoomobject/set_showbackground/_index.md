---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Zoom यह निर्धारित करने के लिए मान सेट करता है कि क्या गंतव्य स्लाइड की पृष्ठभूमि का उपयोग किया जाएगा। प्रकार bool लिखें। डिफ़ॉल्ट मान: true"
type: docs
weight: 66
url: /hi/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) विधि

Zoom यह निर्धारित करने के लिए मान सेट करता है कि क्या गंतव्य स्लाइड की पृष्ठभूमि का उपयोग किया जाएगा। लिखें **bool**। डिफ़ॉल्ट मान: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## टिप्पणियाँ

उदाहरण Zoom ऑब्जेक्ट की छवि की पृष्ठभूमि को हटाने का प्रदर्शन करता है:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## संबंधित देखें

* क्लास [IZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)