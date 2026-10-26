---
title: AddTablePlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड में एक नई प्लेसहोल्डर आकृति जोड़ता है जो तालिका को रखती है।
type: docs
weight: 79
url: /hi/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) मेथड

लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो तालिका को रखता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नई प्लेसहोल्डर आकार का X निर्देशांक। |
| y | **float** | नई प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | **float** | नई प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नई प्लेसहॉल्डर आकार की ऊँचाई। |

### रिटर्न वैल्यू

[IAutoShape](../../iautoshape/) को एक [Table](../../table/) प्लेसहोल्डर के साथ बनाया गया।

## टिप्पणी

निम्न उदाहरण दिखाता है कि कैसे [Table](../../table/) प्लेसहोल्डर आकार को लेआउट स्लाइड में जोड़ा जाता है। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)