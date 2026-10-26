---
title: get_Differential()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Differential이 true이면, 박스는 차동 연산자처럼 동작하고(예: \\uD835\\uDC51\\uD835\\uDC65 in an integrand), 수학적 미분에 적절한 수평 간격을 받습니다. 기본값: false"
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() 메서드

Differential이 true이면, 박스는 미분 연산자처럼 동작하고(예: \\uD835\\uDC51\\uD835\\uDC65 in an integrand), 수학적 미분에 적절한 수평 간격을 받습니다. 기본값: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## 비고

예시:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## 참고

* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)