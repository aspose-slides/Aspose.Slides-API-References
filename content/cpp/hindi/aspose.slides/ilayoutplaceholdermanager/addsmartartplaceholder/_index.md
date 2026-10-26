---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है ताकि एक SmartArt डायाग्राम रखा जा सके।
type: docs
weight: 92
url: /hi/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) मेथड

लेआउट स्लाइड में [SmartArt](../../../aspose.slides.smartart/) डायाग्राम रखने के लिए एक नया प्लेसहोल्डर आकार जोड़ता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### रिटर्न वैल्यू

एक [SmartArt](../../../aspose.slides.smartart/) प्लेसहोल्डर के साथ [IAutoShape](../../iautoshape/) बनाया गया।

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में [SmartArt](../../../aspose.slides.smartart/) प्लेसहोल्डर आकार कैसे जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)