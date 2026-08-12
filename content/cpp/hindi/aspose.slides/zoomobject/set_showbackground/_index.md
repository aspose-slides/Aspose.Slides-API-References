---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Zoom लक्ष्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं, यह निर्धारित करने वाला मान सेट करता है। लिखें bool। डिफ़ॉल्ट मान: true"
type: docs
weight: 66
url: /hi/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) विधि


उस मान को सेट करता है जो निर्धारित करता है कि Zoom लक्ष्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। लिखें **bool**। डिफ़ॉल्ट मान: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## टिप्पणियाँ


उदाहरण दिखाता है कि Zoom ऑब्जेक्ट की छवि से पृष्ठभूमि कैसे हटाई जाए: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## संबंधित देखें

* क्लास [ZoomObject](../)
* नामस्थान [Aspose::Slides](../../)
* पुस्तकालय [Aspose.Slides](../../../)