---
title: get_Base()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() method

Base 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## 비고


예시: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)