---
title: AddMediaPlaceholder()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है ताकि एक मीडिया ऑब्जेक्ट रखा जा सके।
type: docs
weight: 105
url: /hi/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) मेथड

नए प्लेसहोल्डर श形 को लेआउट स्लाइड में जोड़ता है ताकि एक मीडिया ऑब्जेक्ट रखा जा सके।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर श形 का X कॉर्डिनेट। |
| y | **float** | नए प्लेसहोल्डर श形 का Y कॉर्डिनेट। |
| width | **float** | नए प्लेसहोल्डर श形 की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर श形 की ऊँचाई। |

### रिटर्न वैल्यू

एक Media placeholder के साथ [IAutoShape](../../iautoshape/) बनाया गया।

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि कैसे Media placeholder श形 को लेआउट स्लाइड में जोड़ा जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## और देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)