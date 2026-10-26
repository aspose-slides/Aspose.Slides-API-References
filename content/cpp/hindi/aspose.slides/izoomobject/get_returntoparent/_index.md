---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API संदर्भ
description: "स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है। पढ़ें bool। डिफ़ॉल्ट मान: false"
type: docs
weight: 27
url: /hi/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() method


स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है। पढ़ें **bool**। डिफ़ॉल्ट मान: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## टिप्पणी


प्रॉपर्टी का सत्य मान स्लाइडशो में पैरेंट को वापस लौटने के नेविगेशन व्यवहार को निर्दिष्ट करता है। 

उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## संबंधित देखें

* क्लास [IZoomObject](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)