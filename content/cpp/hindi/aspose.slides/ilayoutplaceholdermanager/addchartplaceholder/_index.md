---
title: AddChartPlaceholder()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: लेआउट स्लाइड में चार्ट रखने के लिए एक नया प्लेसहोल्डर आकार जोड़ता है।
type: docs
weight: 66
url: /hi/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) विधि

लेआउट स्लाइड में चार्ट रखने के लिए एक नया प्लेसहोल्डर आकार जोड़ता है।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### रिटर्न वैल्यू

एक Chart प्लेसहोल्डर के साथ बनाया गया [IAutoShape](../../iautoshape/)।

## टिप्पणियाँ

निम्न उदाहरण दर्शाता है कि लेआउट स्लाइड में Chart प्लेसहोल्डर आकार कैसे जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)