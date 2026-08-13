---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 열의 수평 정렬을 설정합니다
type: docs
weight: 248
url: /ko/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) 메서드

지정된 열의 수평 정렬을 설정합니다

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | **int32_t** | 0부터 시작하는 열 인덱스 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 지정된 열의 수평 정렬 새 값 |
## 비고

예시:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## 참조

* 열거형 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)