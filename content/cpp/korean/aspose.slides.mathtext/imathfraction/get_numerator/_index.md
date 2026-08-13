---
title: get_Numerator()
second_title: Aspose.Slides for C++ API 참조
description: 분자
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() 메서드


분자

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
```

## 비고


예시:
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathFraction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)