---
title: get_Denominator()
second_title: Aspose.Slides for C++ API 참조
description: 분모
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() 메서드


분모

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## 비고


예시: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathFraction](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)