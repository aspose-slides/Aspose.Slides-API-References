---
title: AddTextPlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड में टेक्स्ट सामग्री रखने के लिए एक नया प्लेसहोल्डर शैप जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) विधि

नए टेक्स्ट सामग्री को रखने के लिए लेआउट स्लाइड में एक नया प्लेसहोल्डर शैप जोड़ता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर शैप का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर शैप का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर शैप की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर शैप की ऊँचाई। |

### वापसी मान

एक टेक्स्ट प्लेसहोल्डर के साथ बनाया गया [IAutoShape](../../iautoshape/)।

## टिप्पणियाँ

निम्नलिखित उदाहरण दर्शाता है कि लेआउट स्लाइड में टेक्स्ट प्लेसहोल्डर शैप कैसे जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [LayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)