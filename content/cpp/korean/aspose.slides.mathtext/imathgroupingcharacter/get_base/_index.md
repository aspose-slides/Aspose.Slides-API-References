---
title: get_Base()
second_title: Aspose.Slides for C++ API 참조
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathgroupingcharacter/get_base/
---
## IMathGroupingCharacter::get_Base() method

Base 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathGroupingCharacter::get_Base()=0
```

## 비고

예시:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)