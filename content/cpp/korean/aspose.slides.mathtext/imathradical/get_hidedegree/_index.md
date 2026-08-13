---
title: get_HideDegree()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Hide degree가 true이면 차수가 표시되지 않으며, \\u221A\\uD835\\uDC65와 같이 표시됩니다.
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathradical/get_hidedegree/
---
## IMathRadical::get_HideDegree() 메서드

Hide degree가 true이면 차수가 표시되지 않으며, \\u221A\\uD835\\uDC65와 같이 표시됩니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathRadical::get_HideDegree()=0
```

## 비고

예시:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 세제곱근
radical->set_HideDegree(true);
```

## 참고

* 클래스 [IMathRadical](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)