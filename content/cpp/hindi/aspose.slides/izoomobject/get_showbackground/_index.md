---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Zoom यह निर्धारित करने वाला मान प्राप्त करता है कि क्या गंतव्य स्लाइड की पृष्ठभूमि का उपयोग किया जाएगा। पढ़ें bool। डिफ़ॉल्ट मान: true"
type: docs
weight: 53
url: /hi/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() विधि

Zoom यह निर्धारित करने वाला मान प्राप्त करता है कि क्या गंतव्य स्लाइड की पृष्ठभूमि का उपयोग किया जाएगा। पढ़ें **bool**। डिफ़ॉल्ट मान: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## टिप्पणियाँ

यह उदाहरण एक Zoom ऑब्जेक्ट की छवि की पृष्ठभूमि को हटाने को दर्शाता है:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## संबंधित

* वर्ग [IZoomObject](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)