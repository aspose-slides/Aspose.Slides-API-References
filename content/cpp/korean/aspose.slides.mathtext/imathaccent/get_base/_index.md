---
title: get_Base()
second_title: Aspose.Slides C++ API 레퍼런스
description: 악센트가 적용된 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() 메서드


악센트가 적용된 인수

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## 비고


예: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathAccent](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)