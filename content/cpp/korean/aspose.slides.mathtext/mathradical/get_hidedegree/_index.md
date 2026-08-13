---
title: get_HideDegree()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Hide degree가 true이면 차수가 표시되지 않으며, 예를 들어 \\u221A\\uD835\\uDC65
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathradical/get_hidedegree/
---
## MathRadical::get_HideDegree() 메서드

Hide degree가 true이면 차수가 표시되지 않으며, 예를 들어 \\u221A\\uD835\\uDC65

```cpp
bool Aspose::Slides::MathText::MathRadical::get_HideDegree() override
```

## 비고

예시:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
radical->set_HideDegree(true);
```

## 참고

* 클래스 [MathRadical](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)