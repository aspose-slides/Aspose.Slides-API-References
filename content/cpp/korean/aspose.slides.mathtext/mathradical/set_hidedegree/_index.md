---
title: set_HideDegree()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Hide degree가 true이면 차수가 표시되지 않으며, \\u221A\\uD835\\uDC65와 같이 나타납니다.
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathradical/set_hidedegree/
---
## MathRadical::set_HideDegree(bool) method


Hide degree가 true이면 차수가 표시되지 않으며, \\u221A\\uD835\\uDC65와 같이 나타납니다.

```cpp
void Aspose::Slides::MathText::MathRadical::set_HideDegree(bool value) override
```

## Remarks


예: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
radical->set_HideDegree(true);
```

## See Also

* 클래스 [MathRadical](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)