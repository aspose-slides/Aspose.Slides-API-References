---
title: get_TransitionDuration()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Zoom और स्लाइड के बीच संक्रमण की अवधि प्राप्त करता है। float पढ़ें। डिफ़ॉल्ट मान: 1.0f"
type: docs
weight: 105
url: /hi/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() मेथड

Zoom और स्लाइड के बीच संक्रमण की अवधि प्राप्त करता है। पढ़ें **float**। डिफ़ॉल्ट मान: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## टिप्पणी

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड संक्रमण और उस संक्रमण से जुड़े समय का उपयोग करेगा। 

उदाहरण संक्रमण की अवधि को Zoom और स्लाइड के बीच बदलने को दर्शाता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## देखें

* क्लास [IZoomObject](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)