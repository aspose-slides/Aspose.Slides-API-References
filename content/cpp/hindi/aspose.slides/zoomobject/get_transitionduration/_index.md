---
title: get_TransitionDuration()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Zoom और स्लाइड के बीच संक्रमण की अवधि प्राप्त करता है। float पढ़ें। डिफ़ॉल्ट मान: 1.0f"
type: docs
weight: 105
url: /hi/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() विधि

Zoom और स्लाइड के बीच संक्रमण की अवधि प्राप्त करता है। Read **float**. Default value: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## टिप्पणियाँ

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड ट्रांज़िशन और उस ट्रांज़िशन से जुड़े टाइमिंग्स का उपयोग करेगा।

उदाहरण दिखाता है कि Zoom और स्लाइड के बीच संक्रमण की अवधि को कैसे बदलें:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## संबंधित देखें

* वर्ग [ZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)