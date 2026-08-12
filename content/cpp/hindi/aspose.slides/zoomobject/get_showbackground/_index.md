---
title: get_ShowBackground()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "वह मान प्राप्त करता है जो यह निर्धारित करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें bool। डिफ़ॉल्ट मान: true"
type: docs
weight: 53
url: /hi/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() विधि

वह मान प्राप्त करता है जो यह निर्दिष्ट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें **bool**। डिफ़ॉल्ट मान: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## टिप्पणियाँ

यह उदाहरण Zoom ऑब्जेक्ट की छवि की पृष्ठभूमि को हटाने को दर्शाता है: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## संबंधित देखें

* क्लास [ZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)