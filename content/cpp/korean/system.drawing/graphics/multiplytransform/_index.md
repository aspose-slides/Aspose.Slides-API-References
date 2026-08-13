---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 Graphics 객체의 월드 변환 행렬을 지정된 행렬과 곱합니다.
type: docs
weight: 872
url: /ko/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) 메서드


현재 [Graphics](../) 객체의 월드 변환 행렬을 지정된 행렬과 곱합니다.

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 현재 [Graphics](../) 객체의 월드 변환 행렬에 곱할 행렬 |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | 곱셈 순서 |

## 참조

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../../../system.drawing.drawing2d/matrix/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)