---
title: get_Arguments()
second_title: Aspose.Slides for C++ API 참조
description: 구분 문자로 구분된 하나 이상의 수학 요소
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() 메서드


구분 문자로 구분된 하나 이상의 수학 요소

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## 비고


예시: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElementCollection](../../imathelementcollection/)
* 클래스 [MathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)