---
title: Shapes()
second_title: Aspose.Slides for C++ API संदर्भ
description: Presentation में Shape के सभी उदाहरण एकत्र करता है।
type: docs
weight: 1
url: /hi/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) मेथड


[Shape](../../../aspose.slides/shape/) के सभी उदाहरण [Presentation](../../../aspose.slides/presentation/) में संग्रहित करता है।

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) शैप्स को संग्रहित करने के लिए |

### वापसी मान

प्रेजेंटेशन में मौजूद सभी शैप्स का संग्रह

## टिप्पणी




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // यदि shape AutoShape है, तो काली ठोस बॉर्डर जोड़ें
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```




## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IEnumerable](../../../system.collections.generic/ienumerable/)
* क्लास [Shape](../../../aspose.slides/shape/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [Collect](../)
* नामस्थान [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)