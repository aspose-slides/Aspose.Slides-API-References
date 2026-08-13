---
title: get_UpperLimit()
second_title: Aspose.Slides for C++ API 참조
description: 상한 또는 하한을 지정합니다
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathlimit/get_upperlimit/
---
## IMathLimit::get_UpperLimit() 메서드


상한 또는 하한을 지정합니다

```cpp
virtual bool Aspose::Slides::MathText::IMathLimit::get_UpperLimit()=0
```

## 비고


예시:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## 관련 항목

* 클래스 [IMathLimit](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)