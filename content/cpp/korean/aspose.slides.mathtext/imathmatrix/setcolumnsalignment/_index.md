---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 열의 수평 정렬을 설정합니다.
type: docs
weight: 261
url: /ko/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) 메서드


지정된 열의 수평 정렬을 설정합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | **int32_t** | 정렬을 설정할 첫 번째 열의 0부터 시작하는 인덱스 |
| columnsCount | **uint32_t** | 정렬을 지정할 열의 개수 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 지정된 열의 수평 정렬 새 값 |
## 비고



예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## 참조

* 열거형 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)