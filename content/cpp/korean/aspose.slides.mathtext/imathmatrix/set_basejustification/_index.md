---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, 및 center입니다. 기본값: Center"
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/imathmatrix/set_basejustification/
---
## IMathMatrix::set_BaseJustification(MathVerticalAlignment) 메서드

주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, 및 center입니다. 기본값: Center

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_BaseJustification(MathVerticalAlignment value)=0
```

## 비고

예시:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 참조

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)