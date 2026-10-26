---
title: idx_set()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 행렬 요소
type: docs
weight: 222
url: /ko/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) 메서드


행렬 요소

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| row | **int32_t** | 항목을 가져오기 위한 행의 0 기반 인덱스 |
| column | **int32_t** | 항목을 가져오기 위한 열의 0 기반 인덱스 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## 비고



예제: 
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