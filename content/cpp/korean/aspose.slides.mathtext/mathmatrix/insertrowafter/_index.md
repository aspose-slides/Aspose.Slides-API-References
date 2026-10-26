---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 행 뒤에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다.
type: docs
weight: 300
url: /ko/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) 메서드


지정된 행 뒤에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowIndex | **int32_t** | 새 행을 삽입할 행 뒤의 인덱스 |
## 비고


예시: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## 참고

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)