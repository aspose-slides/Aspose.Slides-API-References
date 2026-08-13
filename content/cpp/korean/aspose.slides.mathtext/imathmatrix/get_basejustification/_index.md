---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center이며, 기본값은 Center입니다."
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() 메서드

주변 텍스트에 대해 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center이며, 기본값은 Center입니다.

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## 비고

예시:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 참고

* 열거형 [MathVerticalAlignment](../../mathverticalalignment/)
* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)