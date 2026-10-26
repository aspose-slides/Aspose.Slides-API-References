---
title: GetEffective()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상속이 적용된 효과적인 채우기 서식 데이터를 가져옵니다.
type: docs
weight: 105
url: /ko/aspose.slides/fillformat/geteffective/
---
## FillFormat::GetEffective() 메서드


상속이 적용된 효과적인 채우기 서식 데이터를 가져옵니다.

```cpp
System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::FillFormat::GetEffective() override
```


### 반환값

하나의 [IFillFormatEffectiveData](../../ifillformateffectivedata/).
## 비고



이 예제는 도형의 효과적인 채우기 서식 속성을 가져오는 방법을 보여줍니다. 
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

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* Class [FillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)