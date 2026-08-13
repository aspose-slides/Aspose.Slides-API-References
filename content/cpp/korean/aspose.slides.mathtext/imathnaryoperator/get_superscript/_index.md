---
title: get_Superscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 예를 들어 적분의 경우와 같이 위첨자 인수를 지정하며, 상한을 설정합니다.
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() 메서드

예를 들어 적분의 경우와 같이 위첨자 인수를 지정하며, 해당 인수는 상한을 설정합니다.

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## 비고


예: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)