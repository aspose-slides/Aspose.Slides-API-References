---
title: DeleteColumn()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 열을 삭제합니다.
type: docs
weight: 352
url: /ko/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) 메서드

지정된 열을 삭제합니다.

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | **int32_t** | 삭제할 열의 0부터 시작하는 인덱스입니다. |

## 비고



예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## 참고

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)