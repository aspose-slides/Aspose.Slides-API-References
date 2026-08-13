---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 열의 수평 정렬을 설정합니다
type: docs
weight: 261
url: /ko/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) 메서드


지정된 열의 수평 정렬을 설정합니다

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | 0부터 시작하는 열 인덱스 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 지정된 열의 수평 정렬 새 값 |
## 비고



예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## 참조

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)