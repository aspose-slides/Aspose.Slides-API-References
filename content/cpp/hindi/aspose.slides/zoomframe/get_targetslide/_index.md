---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API संदर्भ
description: Slide Zoom ऑब्जेक्ट द्वारा लिंक किए गए स्लाइड ऑब्जेक्ट को प्राप्त करता है। पढ़ें ISlide.
type: docs
weight: 1
url: /hi/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() मेथड

वह स्लाइड ऑब्जेक्ट प्राप्त करता है जिसे [Slide](../../slide/) Zoom ऑब्जेक्ट लिंक करता है। पढ़ें [ISlide](../../islide/)।

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```
## टिप्पणी

अगला उदाहरण टार्गेट स्लाइड को बदलते हुए दिखाता है और [Slide](../../slide/) Zoom ऑब्जेक्ट के लिए नई छवि बनाता है:
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