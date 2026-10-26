---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 열 뒤에 새 열을 삽입합니다. 처음에 새 열의 모든 요소는 null입니다.
type: docs
weight: 339
url: /ko/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) 메서드


지정된 열 뒤에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | **int32_t** | Index of the column after which to insert a new one |
## 비고



예제: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## 참조

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)