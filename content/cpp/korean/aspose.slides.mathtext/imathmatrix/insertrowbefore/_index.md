---
title: InsertRowBefore()
second_title: Aspose.Slides C++ API 참조
description: 지정된 행 앞에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다.
type: docs
weight: 274
url: /ko/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) 메서드


지정된 행 앞에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowIndex | **int32_t** | 새 행을 삽입할 행 앞의 인덱스 |
## 비고



예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## 참고

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)