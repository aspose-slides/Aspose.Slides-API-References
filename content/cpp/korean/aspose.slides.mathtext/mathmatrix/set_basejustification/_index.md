---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API 참조
description: "주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom 및 center이며, 기본값은 Center입니다."
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) 메서드

주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom 및 center이며, 기본값은 Center입니다.

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## 비고

예시:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 참고

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)