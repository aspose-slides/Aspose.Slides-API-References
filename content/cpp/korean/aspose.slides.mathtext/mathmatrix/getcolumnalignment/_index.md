---
title: GetColumnAlignment()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 열의 수평 정렬을 가져옵니다
type: docs
weight: 248
url: /ko/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) 메서드

지정된 열의 수평 정렬을 가져옵니다

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | **int32_t** | 0부터 시작하는 열 인덱스 |

### 반환값

지정된 열의 수평 정렬

## 비고



예시: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## 참고

* 열거형 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)