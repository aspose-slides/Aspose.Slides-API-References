---
title: set_TransitionDuration()
second_title: Aspose.Slides का C++ API संदर्भ
description: "Zoom और स्लाइड के बीच संक्रमण की अवधि निर्धारित करता है। float लिखें। डिफ़ॉल्ट मान: 1.0f"
type: docs
weight: 118
url: /hi/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) विधि


Zoom और स्लाइड के बीच संक्रमण की अवधि निर्धारित करता है। **float** लिखें। डिफ़ॉल्ट मान: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## टिप्पणियाँ


यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड संक्रमण और उस संक्रमण से संबंधित समय-सारिणी का उपयोग करेगा। 

उदाहरण Zoom और स्लाइड के बीच संक्रमण की अवधि बदलने को प्रदर्शित करता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## संबंधित देखें

* क्लास [IZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)