---
title: GetEffective()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: विरासत लागू होने के साथ प्रभावी भाग स्वरूप डेटा प्राप्त करता है।
type: docs
weight: 131
url: /hi/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() विधि


विरासत लागू होने के साथ प्रभावी भाग स्वरूप डेटा प्राप्त करता है।

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### रिटर्न वैल्यू

एक [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## टिप्पणी



यह उदाहरण प्रभावी भाग स्वरूप गुणों को प्राप्त करने का प्रदर्शन करता है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* क्लास [PortionFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)