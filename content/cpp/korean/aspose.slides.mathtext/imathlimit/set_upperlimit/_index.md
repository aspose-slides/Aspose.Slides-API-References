---
title: set_UpperLimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상한 또는 하한을 지정합니다
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) 메서드


상한 또는 하한을 지정합니다

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## 비고


예:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## 참고

* 클래스 [IMathLimit](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)