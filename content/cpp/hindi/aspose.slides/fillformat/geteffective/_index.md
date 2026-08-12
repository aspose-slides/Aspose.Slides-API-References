---
title: GetEffective()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: विरासत लागू होने के साथ प्रभावी भराव स्वरूपण डेटा प्राप्त करता है।
type: docs
weight: 105
url: /hi/aspose.slides/fillformat/geteffective/
---
## FillFormat::GetEffective() विधि

विरासत लागू होने के साथ प्रभावी भराव स्वरूपण डेटा प्राप्त करता है।

```cpp
System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::FillFormat::GetEffective() override
```

### वापसी मान

एक [IFillFormatEffectiveData](../../ifillformateffectivedata/).
## टिप्पणियाँ

यह उदाहरण आकार की प्रभावी भराव स्वरूप गुण प्राप्त करने को दर्शाता है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveFillFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_FillFormat()->GetEffective();

Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(effectiveFillFormat->get_FillType()));
switch (effectiveFillFormat->get_FillType())
{
    case FillType::Solid:
        Console::WriteLine(String(u"Fill color: ") + effectiveFillFormat->get_SolidFillColor());
        break;

    case FillType::Pattern:
        Console::WriteLine(String(u"Pattern style: ") + ObjectExt::ToString(effectiveFillFormat->get_PatternFormat()->get_PatternStyle()));
        Console::WriteLine(String(u"Fore color: ") + effectiveFillFormat->get_PatternFormat()->get_ForeColor());
        Console::WriteLine(String(u"Back color: ") + effectiveFillFormat->get_PatternFormat()->get_BackColor());
        break;

    case FillType::Gradient:
        Console::WriteLine(String(u"Gradient direction: ") + ObjectExt::ToString(effectiveFillFormat->get_GradientFormat()->get_GradientDirection()));
        Console::WriteLine(String(u"Gradient stops count: ") + effectiveFillFormat->get_GradientFormat()->get_GradientStops()->get_Count());
        break;

    case FillType::Picture:
        Console::WriteLine(String(u"Picture width: ") + effectiveFillFormat->get_PictureFillFormat()->get_Picture()->get_Image()->get_Width());
        Console::WriteLine(String(u"Picture height: ") + effectiveFillFormat->get_PictureFillFormat()->get_Picture()->get_Image()->get_Height());
        break;

    default:
        break;
}
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* क्लास [FillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)