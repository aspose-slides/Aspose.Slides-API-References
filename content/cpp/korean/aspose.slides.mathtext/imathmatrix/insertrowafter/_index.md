---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 행 뒤에 새 행을 삽입합니다. 새 행의 모든 요소는 초기값으로 null입니다.
type: docs
weight: 287
url: /ko/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) 메서드

새 행을 지정된 행 뒤에 삽입합니다. 새 행의 모든 요소는 초기값으로 null입니다.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowIndex | **int32_t** | 새 행을 삽입할 행의 인덱스 |
## 비고



예시: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## 참조

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)