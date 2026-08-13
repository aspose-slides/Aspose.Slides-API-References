---
title: get_Base()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_base/
---
## IMathRightSubSuperscriptElement::get_Base() 메서드


Base 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Base()=0
```

## 비고


예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = subsuperscript->get_Base();
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathRightSubSuperscriptElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)