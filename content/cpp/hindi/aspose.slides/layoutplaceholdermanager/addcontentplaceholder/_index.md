---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड में नई प्लेसहोल्डर आकृति जोड़ता है ताकि चित्र, तालिका, मीडिया या टेक्स्ट जैसी सामग्री रखी जा सके।
type: docs
weight: 1
url: /hi/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) method


नए प्लेसहोल्डर आकार को लेआउट स्लाइड में कंटेंट जैसे चित्र, तालिका, मीडिया या टेक्स्ट रखने के लिए जोड़ेगा।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```


### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर आकार की X निर्देशांक। |
| y | **float** | नए प्लेसहोल्डर आकार की Y निर्देशांक। |
| width | **float** | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर आकार की ऊँचाई। |

### वापसी मान

एक Content प्लेसहोल्डर के साथ [IAutoShape](../../iautoshape/) बनाया गया।

## टिप्पणी



निम्नलिखित उदाहरण दिखाता है कि लेआउट स्लाइड में Content प्लेसहोल्डर आकार कैसे जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [LayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)