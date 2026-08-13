---
title: get_Superscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 위첨자
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_superscript/
---
## MathLeftSubSuperscriptElement::get_Superscript() 메서드


위첨자

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Superscript() override
```

## 비고


예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathLeftSubSuperscriptElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)