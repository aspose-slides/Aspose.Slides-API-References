---
title: GetEffective()
second_title: Aspose.Slides for C++ API 참조
description: 상속이 적용된 효과적인 부분 서식 데이터를 가져옵니다.
type: docs
weight: 131
url: /ko/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() 메서드


상속이 적용된 효과적인 부분 서식 데이터를 가져옵니다.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### 반환 값

하나의 [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## 비고



이 예제는 일부 효과적인 부분 서식 속성을 가져오는 방법을 보여줍니다. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* 클래스 [PortionFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)