---
title: AddMediaPlaceholder()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है ताकि मीडिया ऑब्जेक्ट रखा जा सके।
type: docs
weight: 105
url: /hi/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) method

नए प्लेसहोल्डर आकार को लेआउट स्लाइड में जोड़ता है ताकि एक मीडिया ऑब्जेक्ट रखा जा सके।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X कोऑर्डिनेट। |
| y | **float** | नए प्लेसहोल्डर आकार का Y कोऑर्डिनेट। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### रिटर्न मान

Created [IAutoShape](../../iautoshape/) with a Media placeholder.

## टिप्पणियाँ

निम्नलिखित उदाहरण दिखाता है कि कैसे Media प्लेसहोल्डर आकार को लेआउट स्लाइड में जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)