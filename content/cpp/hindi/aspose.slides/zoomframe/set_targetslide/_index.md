---
title: set_TargetSlide()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: Slide Zoom ऑब्जेक्ट द्वारा लिंक किए जाने वाले स्लाइड ऑब्जेक्ट को सेट करता है। लिखें ISlide.
type: docs
weight: 14
url: /hi/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) मेथड


स्लाइड ऑब्जेक्ट सेट करता है जिसे [Slide](../../slide/) ज़ूम ऑब्जेक्ट लिंक करता है। लिखें [ISlide](../../islide/)।

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## टिप्पणियाँ


अगला उदाहरण लक्ष्य स्लाइड को बदलने और [Slide](../../slide/) ज़ूम ऑब्जेक्ट के लिए नई छवि बनाने का प्रदर्शन करता है: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [ZoomFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)