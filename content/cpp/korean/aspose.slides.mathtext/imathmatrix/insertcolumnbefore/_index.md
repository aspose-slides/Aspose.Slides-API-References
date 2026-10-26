---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 열 앞에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다.
type: docs
weight: 313
url: /ko/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) 메서드


지정된 열 앞에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | **int32_t** | 새 열을 삽입할 열 앞의 인덱스 |
## 비고



예:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## 참고

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)