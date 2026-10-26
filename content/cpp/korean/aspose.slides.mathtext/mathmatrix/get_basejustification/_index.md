---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center이며 기본값은 Center입니다."
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() 메서드


주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center입니다. 기본값: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## 비고


예:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 참조

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)