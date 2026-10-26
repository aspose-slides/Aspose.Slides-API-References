---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड में नई प्लेसहोल्डर शैक जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट को वर्टिकल दिशा में रखता है।
type: docs
weight: 14
url: /hi/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) method

नए प्लेसहोल्डर शैक को लेआउट स्लाइड में जोड़ता है जो सामग्री को रखता है, जैसे चित्र, तालिका, मीडिया या टेक्स्ट को वर्टिकल दिशा में।

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए प्लेसहोल्डर शैक का X समन्वय। |
| y | **float** | नए प्लेसहोल्डर शैक का Y समन्वय। |
| width | **float** | नए प्लेसहोल्डर शैक की चौड़ाई। |
| height | **float** | नए प्लेसहोल्डर शैक की ऊँचाई। |

### रिटर्न वैल्यू

Created [IAutoShape](../../iautoshape/) with a Content (Vertical) placeholder.

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि कैसे Content (Vertical) प्लेसहोल्डर शैक को लेआउट स्लाइड में जोड़ा जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)