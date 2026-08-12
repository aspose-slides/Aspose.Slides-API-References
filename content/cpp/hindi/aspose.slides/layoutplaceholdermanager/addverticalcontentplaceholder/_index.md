---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया प्लेसहोल्डर आकार लेआउट स्लाइड में जोड़ता है ताकि सामग्री, जैसे चित्र, टेबल, मीडिया या टेक्स्ट को लंबवत दिशा में रखा जा सके।
type: docs
weight: 14
url: /hi/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) method

नया प्लेसहोल्डर शैप लेआउट स्लाइड में जोड़ता है जो सामग्री जैसे चित्र, टेबल, मीडिया या टेक्स्ट को लंबवत दिशा में रखता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर शैप का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर शैप का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर शैप की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर शैप की ऊँचाई। |

### वापसी मान

[IAutoShape](../../iautoshape/) को एक Content (Vertical) प्लेसहोल्डर के साथ बनाया गया।

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Content (Vertical) प्लेसहोल्डर शैप कैसे जोड़ा जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## संबंधित

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [LayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)