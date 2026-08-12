--- 
title: set_ReturnToParent()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "स्लाइडशो में नेविगेशन व्यवहार निर्धारित करता है। bool लिखें। डिफ़ॉल्ट मान: false"
type: docs
weight: 40
url: /hi/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) विधि


स्लाइडशो में नेविगेशन व्यवहार सेट करता है। **bool** लिखें। डिफ़ॉल्ट मान: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## टिप्पणी


प्रॉपर्टी का true मान स्लाइडशो में पैरेंट पर लौटने का नेविगेशन व्यवहार निर्दिष्ट करता है।

उदाहरण: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## देखें

* क्लास [ZoomObject](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)