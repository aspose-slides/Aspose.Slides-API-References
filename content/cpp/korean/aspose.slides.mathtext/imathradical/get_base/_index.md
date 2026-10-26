---
title: get_Base()
second_title: C++용 Aspose.Slides API 레퍼런스
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() 메서드


Base 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## 비고


예시: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 세제곱근
auto baseElem = radical->get_Base();
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathRadical](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)