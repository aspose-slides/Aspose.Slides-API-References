---
title: get_Superscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 예를 들어 적분의 경우와 같이 상한을 설정하는 위첨자 인자를 지정합니다.
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() method

예를 들어 적분의 경우와 같이 상한을 설정하는 위첨자 인자를 지정합니다.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```
## 비고


예시: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)