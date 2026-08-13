---
title: DeleteRow()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 행을 삭제합니다
type: docs
weight: 300
url: /ko/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) 메서드

지정된 행을 삭제합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowIndex | **int32_t** | 삭제할 행의 0 기반 인덱스. |
## 비고



예시: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## 또한 보기

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)