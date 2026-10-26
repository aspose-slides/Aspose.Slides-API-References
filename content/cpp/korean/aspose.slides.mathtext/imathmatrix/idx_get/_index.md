---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: 행렬 요소
type: docs
weight: 209
url: /ko/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) 메서드

행렬의 요소

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| row | **int32_t** | 항목을 가져올 행의 0부터 시작하는 인덱스 |
| column | **int32_t** | 항목을 가져올 열의 0부터 시작하는 인덱스 |

### 반환 값


## 비고



예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)