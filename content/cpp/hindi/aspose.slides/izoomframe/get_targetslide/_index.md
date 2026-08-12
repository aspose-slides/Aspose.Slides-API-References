---
title: get_TargetSlide()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Slide Zoom ऑब्जेक्ट द्वारा लिंक किए गए स्लाइड ऑब्जेक्ट को प्राप्त करता है। पढ़ें ISlide।
type: docs
weight: 1
url: /hi/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() मेथड


उस [Slide](../../slide/) ज़ूम ऑब्जेक्ट द्वारा लिंक किए गए स्लाइड ऑब्जेक्ट को प्राप्त करता है। पढ़ें [ISlide](../../islide/)।

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## टिप्पणियाँ


अगला उदाहरण लक्ष्य स्लाइड को बदलने और [Slide](../../slide/) ज़ूम ऑब्जेक्ट के लिए नई छवि बनाने को प्रदर्शित करता है: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [IZoomFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)