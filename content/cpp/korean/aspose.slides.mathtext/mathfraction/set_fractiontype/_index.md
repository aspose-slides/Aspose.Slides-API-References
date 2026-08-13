---
title: set_FractionType()
second_title: Aspose.Slides C++ API 레퍼런스
description: "분수 유형 기본값: Bar"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathfraction/set_fractiontype/
---
## MathFraction::set_FractionType(MathFractionTypes) 메서드


분수 유형 기본값: Bar

```cpp
void Aspose::Slides::MathText::MathFraction::set_FractionType(MathFractionTypes value) override
```

## 비고


예제: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## 참고

* 열거형 [MathFractionTypes](../../mathfractiontypes/)
* 클래스 [MathFraction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)