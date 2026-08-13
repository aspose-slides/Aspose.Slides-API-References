---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 행 앞에 새로운 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다.
type: docs
weight: 287
url: /ko/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) 메서드


지정된 행 앞에 새로운 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rowIndex | **int32_t** | 새 행을 삽입할 이전 행의 인덱스 |
## 비고



예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## 참조

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)