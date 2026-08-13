---
title: DeleteRow()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 행을 삭제합니다
type: docs
weight: 313
url: /ko/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) 메서드

지정된 행을 삭제합니다

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowIndex | **int32_t** | 삭제할 행의 0부터 시작하는 인덱스입니다. |

## 비고



예시: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## 참고

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)