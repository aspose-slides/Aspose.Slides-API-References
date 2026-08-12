---
title: AddChartPlaceholder()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: लेआउट स्लाइड में एक चार्ट रखने के लिए एक नया प्लेसहोल्डर आकार जोड़ता है।
type: docs
weight: 66
url: /hi/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) मेथड

लेआउट स्लाइड में एक Chart रखने के लिए एक नया प्लेसहोल्डर आकार जोड़ता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### आर्गुमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | The X coordinate of the new placeholder shape. |
| y | **float** | The Y coordinate of the new placeholder shape. |
| width | **float** | The width of the new placeholder shape. |
| height | **float** | The height of the new placeholder shape. |

### वापसी मान

[IAutoShape](../../iautoshape/) को एक Chart placeholder के साथ बनाया गया।

## टिप्पणी

निम्न उदाहरण दर्शाता है कि कैसे लेआउट स्लाइड में Chart प्लेसहोल्डर आकार जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [LayoutPlaceholderManager](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)