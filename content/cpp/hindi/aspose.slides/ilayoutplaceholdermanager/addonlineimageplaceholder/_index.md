---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक ऑनलाइन छवि रखने के लिए लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है।
type: docs
weight: 118
url: /hi/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) मेथड

लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है ताकि ऑनलाइन छवि रखी जा सके।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### रिटर्न वैल्यू

[IAutoShape](../../iautoshape/) बनाया गया जिसमें एक ऑनलाइन इमेज प्लेसहोल्डर है।

## टिप्पणी

निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में ऑनलाइन इमेज प्लेसहोल्डर आकार कैसे जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)