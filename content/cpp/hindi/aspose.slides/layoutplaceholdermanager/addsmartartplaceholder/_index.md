---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक SmartArt आरेख रखता है।
type: docs
weight: 92
url: /hi/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) मेथड


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक [SmartArt](../../../aspose.slides.smartart/) आरेख रखता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### वापसी मान

एक [SmartArt](../../../aspose.slides.smartart/) प्लेसहोल्डर के साथ [IAutoShape](../../iautoshape/) बनाया गया।

## टिप्पणी


निम्नलिखित उदाहरण दिखाता है कि लेआउट स्लाइड में [SmartArt](../../../aspose.slides.smartart/) प्लेसहोल्डर आकार को कैसे जोड़ा जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [LayoutPlaceholderManager](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)