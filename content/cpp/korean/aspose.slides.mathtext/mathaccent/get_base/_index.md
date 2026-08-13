---
title: get_Base()
second_title: Aspose.Slides for C++ API 레퍼런스
description: accent가 적용된 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() 메서드


accent가 적용된 인수

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## 비고


예: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathAccent](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)