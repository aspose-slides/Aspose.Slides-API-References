---
title: idx_get()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 행렬 요소
type: docs
weight: 209
url: /ko/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) 메서드

행렬 요소

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| row | **int32_t** | 항목을 가져오기 위한 행의 0 기반 인덱스 |
| column | **int32_t** | 항목을 가져오기 위한 열의 0 기반 인덱스 |

### 반환 값


## 비고



예시: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)