---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Zoom और स्लाइड के बीच संक्रमण की अवधि सेट करता है। लिखें float। डिफ़ॉल्ट मान: 1.0f"
type: docs
weight: 118
url: /hi/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) विधि

Zoom और स्लाइड के बीच संक्रमण की अवधि सेट करता है। लिखें **float**। डिफ़ॉल्ट मान: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## टिप्पणियाँ

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), यह गंतव्य स्लाइड संक्रमण और उस संक्रमण से जुड़े समय का उपयोग करेगा।

उदाहरण दर्शाता है कि Zoom और स्लाइड के बीच संक्रमण की अवधि कैसे बदलें:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## देखें

* क्लास [ZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)