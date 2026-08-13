---
title: MathSubscriptElement()
second_title: Aspose.Slides for C++ API 참조
description: MathSubscriptElement 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathsubscriptelement/mathsubscriptelement/
---
## MathSubscriptElement::MathSubscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 생성자

새로운 [MathSubscriptElement](../) 클래스의 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathSubscriptElement::MathSubscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript)
```

## 비고

예제:
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathSubscriptElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)