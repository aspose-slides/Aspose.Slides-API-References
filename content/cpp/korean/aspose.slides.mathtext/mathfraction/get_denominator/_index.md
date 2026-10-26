---
title: get_Denominator()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 분모
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() 메서드


분모

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
```

## 비고


예시: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathFraction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)