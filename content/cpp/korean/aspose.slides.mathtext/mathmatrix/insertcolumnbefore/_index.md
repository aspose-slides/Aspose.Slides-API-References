---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 열 앞에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다.
type: docs
weight: 326
url: /ko/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) method


지정된 열 앞에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | **int32_t** | 새 열을 삽입할 열의 앞쪽 인덱스 |
## 비고



예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## 또한 보기

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)