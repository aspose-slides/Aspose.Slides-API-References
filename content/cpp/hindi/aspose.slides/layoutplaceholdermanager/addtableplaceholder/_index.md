---
title: AddTablePlaceholder()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है ताकि टेबल रखा जा सके।
type: docs
weight: 79
url: /hi/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) मेथड

नया टेबल रखने के लिए लेआउट स्लाइड में एक नया प्लेसहोल्डर शेप जोड़ता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नया प्लेसहोल्डर शेप का X निर्देशांक। |
| y | **float** | नया प्लेसहोल्डर शेप का Y निर्देशांक। |
| width | **float** | नया प्लेसहोल्डर शेप की चौड़ाई। |
| height | **float** | नया प्लेसहोल्डर शेप की ऊँचाई। |

### वापसी मान

[IAutoShape](../../iautoshape/) बनाया गया एक [Table](../../table/) प्लेसहोल्डर के साथ।

## टिप्पणी

निम्न उदाहरण दिखाता है कि [Table](../../table/) प्लेसहोल्डर शेप को लेआउट स्लाइड में कैसे जोड़ा जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [LayoutPlaceholderManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)