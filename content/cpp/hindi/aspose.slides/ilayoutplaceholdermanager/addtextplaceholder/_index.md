---
title: AddTextPlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड में टेक्स्ट सामग्री रखने के लिए एक नया प्लेसहोल्डर शैप जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) विधि

लेआउट स्लाइड में टेक्स्ट सामग्री रखने के लिए एक नया प्लेसहोल्डर शैप जोड़ता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर शैप का X कॉर्डिनेट। |
| y | **float** | नए प्लेसहोल्डर शैप का Y कॉर्डिनेट। |
| width | **float** | नए प्लेसहोल्डर शैप की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर शैप की ऊँचाई। |

### रिटर्न वैल्यू

एक टेक्स्ट प्लेसहोल्डर के साथ [IAutoShape](../../iautoshape/) बनाया गया।

## टिप्पणी

निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में टेक्स्ट प्लेसहोल्डर शैप कैसे जोड़ा जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)