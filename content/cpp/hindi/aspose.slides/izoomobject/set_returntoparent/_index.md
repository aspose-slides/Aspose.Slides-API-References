---
title: set_ReturnToParent()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "स्लाइडशो में नेविगेशन व्यवहार सेट करता है। bool लिखें। डिफ़ॉल्ट मान: false"
type: docs
weight: 40
url: /hi/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) विधि

स्लाइडशो में नेविगेशन व्यवहार सेट करता है। **bool** लिखें। डिफ़ॉल्ट मान: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## टिप्पणी

प्रॉपर्टी का True मान स्लाइडशो में पैरेंट पर लौटने के नेविगेशन व्यवहार को निर्दिष्ट करता है।

उदाहरण:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## देखें

* वर्ग [IZoomObject](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)