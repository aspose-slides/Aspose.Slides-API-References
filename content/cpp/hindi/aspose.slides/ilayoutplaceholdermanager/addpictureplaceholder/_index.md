---
title: AddPicturePlaceholder()
second_title: Aspose.Slides का C++ API संदर्भ
description: लेआउट स्लाइड में एक नई प्लेसहोल्डर आकृति जोड़ता है जो एक चित्र रखेगी।
type: docs
weight: 53
url: /hi/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) मेथड

लेआउट स्लाइड में एक नई प्लेसहोल्डर आकृति जोड़ता है जो एक चित्र रखेगी।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नई प्लेसहोल्डर आकृति का X निर्देशांक। |
| y | **float** | नई प्लेसहोल्डर आकृति का Y निर्देशांक। |
| width | **float** | नई प्लेसहोल्डर आकृति की चौड़ाई। |
| height | **float** | नई प्लेसहोल्डर आकृति की ऊँचाई। |

### रिटर्न मान

[IAutoShape](../../iautoshape/) को एक [Picture](../../picture/) प्लेसहोल्डर के साथ बनाया गया।

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में [Picture](../../picture/) प्लेसहोल्डर आकृति कैसे जोड़ी जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## संदर्भ

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ILayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)