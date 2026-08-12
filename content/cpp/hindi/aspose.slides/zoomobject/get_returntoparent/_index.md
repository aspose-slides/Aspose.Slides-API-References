---
title: get_ReturnToParent()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है। पढ़ें bool। डिफ़ॉल्ट मान: false"
type: docs
weight: 27
url: /hi/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() विधि

स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है। पढ़ें **bool**। डिफ़ॉल्ट मान: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## टिप्पणियां

संपत्ति का true मान स्लाइडशो में पैरेंट पर वापस जाने के नेविगेशन व्यवहार को निर्दिष्ट करता है।

उदाहरण: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## संबंधित देखें

* क्लास [ZoomObject](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)