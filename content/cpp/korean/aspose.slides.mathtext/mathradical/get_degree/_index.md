---
title: get_Degree()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Degree 인수
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() 메서드

Degree 인수

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## 비고

예제:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathRadical](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)