---
title: AddPicturePlaceholder()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: लेआउट स्लाइड में एक नई प्लेसहोल्डर आकार जोड़ता है जिससे चित्र रखा जा सके।
type: docs
weight: 53
url: /hi/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) विधि

लेआउट स्लाइड में एक नई प्लेसहोल्डर आकार जोड़ता है जिसे चित्र रखने के लिए उपयोग किया जाता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### वापसी मान

[IAutoShape](../../iautoshape/) बनाया गया एक [Picture](../../picture/) प्लेसहोल्डर के साथ।

## टिप्पणी

निम्न उदाहरण दिखाता है कि कैसे [Picture](../../picture/) प्लेसहोल्डर आकार को लेआउट स्लाइड में जोड़ा जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [LayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)