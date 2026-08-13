---
title: get_FractionType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "분수 형식 기본값: Bar"
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathfraction/get_fractiontype/
---
## MathFraction::get_FractionType() 메서드


분수 형식 기본값: Bar

```cpp
MathFractionTypes Aspose::Slides::MathText::MathFraction::get_FractionType() override
```

## 비고


예: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 참고

* 열거형 [MathFractionTypes](../../mathfractiontypes/)
* 클래스 [MathFraction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)