---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है ताकि टेक्स्ट सामग्री को लंबवत दिशा में रखा जा सके।
type: docs
weight: 40
url: /hi/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) विधि

एक नया प्लेसहोल्डर आकार लेआउट स्लाइड में जोड़ता है ताकि टेक्स्ट सामग्री को लंबवत दिशा में रखा जा सके।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | **float** | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### रिटर्न मान

[IAutoShape](../../iautoshape/) को एक Text (Vertical) प्लेसहोल्डर के साथ बनाया गया।

## टिप्पणी

निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Text (Vertical) प्लेसहोल्डर आकार को कैसे जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)