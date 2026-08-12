---
title: set_TargetSlide()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक स्लाइड ऑब्जेक्ट सेट करता है जिसे Slide Zoom ऑब्जेक्ट लिंक करता है। लिखें ISlide.
type: docs
weight: 14
url: /hi/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) विधि

स्लाइड ऑब्जेक्ट को सेट करता है जो [Slide](../../slide/) Zoom ऑब्जेक्ट द्वारा लिंक किया जाता है। लिखें [ISlide](../../islide/)।

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## टिप्पणी

अगला उदाहरण लक्ष्य स्लाइड को बदलने और [Slide](../../slide/) Zoom ऑब्जेक्ट के लिए नई छवि बनाने को दर्शाता है:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [IZoomFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)