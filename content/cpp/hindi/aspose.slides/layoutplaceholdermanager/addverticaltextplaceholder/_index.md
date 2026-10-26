---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री को लंबवत दिशा में रखने के लिए उपयोग होता है।
type: docs
weight: 40
url: /hi/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) विधि

लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री को लंबवत दिशा में रखने के लिए उपयोग होता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### वापसी मान

[IAutoShape](../../iautoshape/) बनाया गया है एक टेक्स्ट (Vertical) प्लेसहोल्डर के साथ।

## टिप्पणी

निम्न उदाहरण दिखाता है कि कैसे लेआउट स्लाइड में टेक्स्ट (Vertical) प्लेसहोल्डर आकार जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [LayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)