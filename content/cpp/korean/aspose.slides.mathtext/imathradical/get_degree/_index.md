---
title: get_Degree()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Degree 인수
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() 메서드


Degree 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## 비고


예시: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 세제곱근
auto degreeElem = radical->get_Degree();
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathRadical](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)