---
title: GetEffective()
second_title: C++용 Aspose.Slides API 참조
description: 상속이 적용된 실제 텍스트 프레임 서식 데이터를 가져옵니다.
type: docs
weight: 391
url: /ko/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() 메서드


상속이 적용된 실제 텍스트 프레임 서식 데이터를 가져옵니다.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### 반환 값

하나의 [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## 비고



이 예제는 일부 효과적인 텍스트 프레임 서식 속성을 가져오는 방법을 보여줍니다.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* 클래스 [TextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)