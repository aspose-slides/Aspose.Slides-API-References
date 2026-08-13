---
title: set_Differential()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Differential true이면, 상자는 미분 연산자 역할을 하며 (예: \\uD835\\uDC51\\uD835\\uDC65 를 적분식에 사용할 때), 수학적 미분에 필요한 적절한 수평 간격을 받습니다. 기본값: false"
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) 메서드

Differential When true, the box acts as a differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. 기본값: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## 비고

Example: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 참조

* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)