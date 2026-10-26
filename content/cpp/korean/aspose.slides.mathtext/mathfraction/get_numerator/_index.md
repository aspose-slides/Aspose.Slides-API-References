---
title: get_Numerator()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 분자
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() 메서드


분자

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## 비고


예시: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathFraction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)