---
title: get_InkEffect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "잉크 스트로크의 시각적 스타일을 정의하는 잉크 효과 유형(예: Galaxy, Gold, Silver)을 가져옵니다. 이 값은 브러시 속성 \"inkEffects\"에서 구문 분석됩니다. 인식된 효과가 지정되지 않은 경우 InkEffectType::NotDefined이 반환됩니다."
type: docs
weight: 53
url: /ko/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() 메서드

잉크 스트로크의 시각적 스타일을 정의하는 잉크 효과 유형(예: Galaxy, Gold, Silver)을 가져옵니다. 이 값은 브러시 속성 \"inkEffects\"에서 구문 분석됩니다. 인식된 효과가 지정되지 않은 경우, [InkEffectType::NotDefined](../../inkeffecttype/)가 반환됩니다.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## 비고

예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## 참조

* Enum [InkEffectType](../../inkeffecttype/)
* Class [IInkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)