---
title: get_Subscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하위 스크립트 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_subscript/
---
## MathRightSubSuperscriptElement::get_Subscript() 메서드

하위 스크립트 인수

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Subscript() override
```

## 비고

예제:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscripts->get_Subscript();
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathRightSubSuperscriptElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)