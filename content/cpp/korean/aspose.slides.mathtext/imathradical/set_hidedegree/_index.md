---
title: set_HideDegree()
second_title: Aspose.Slides for C++ API 참조
description: 숨김 차수: true이면 차수가 표시되지 않으며, \\u221A\\uD835\\uDC65와 같이 나타납니다.
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathradical/set_hidedegree/
---
## IMathRadical::set_HideDegree(bool) 메서드

숨김 차수: true이면 차수가 표시되지 않으며, \\u221A\\uD835\\uDC65와 같이 나타납니다.

```cpp
virtual void Aspose::Slides::MathText::IMathRadical::set_HideDegree(bool value)=0
```

## 비고

예:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 세제곱근
radical->set_HideDegree(true);
```

## 관련 항목

* 클래스 [IMathRadical](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)