---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड में सामग्री रखने के लिए, जैसे चित्र, तालिका, मीडिया या टेक्स्ट, एक नया प्लेसहोल्डर आकार जोड़ता है।
type: docs
weight: 1
url: /hi/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) method

लेआउट स्लाइड में सामग्री रखने के लिए, जैसे कि चित्र, तालिका, मीडिया या टेक्स्ट, एक नया प्लेसहोल्डर आकार जोड़ता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### Return Value

एक कंटेंट प्लेसहोडर के साथ [IAutoShape](../../iautoshape/) बनाया गया।

## Remarks

निम्नलिखित उदाहरण दिखाता है कि लेआउट स्लाइड में कंटेंट प्लेसहोल्डर आकार कैसे जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## See Also

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)