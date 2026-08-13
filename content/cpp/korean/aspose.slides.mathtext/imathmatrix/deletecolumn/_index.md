---
title: DeleteColumn()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 열을 삭제합니다.
type: docs
weight: 339
url: /ko/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) 메서드

지정된 열을 삭제합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | **int32_t** | 삭제할 열의 0 기반 인덱스입니다. |
## 비고



예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## 참조

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)