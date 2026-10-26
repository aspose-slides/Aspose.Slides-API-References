---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 행렬에 의해 현재 객체의 변환 행렬을 곱합니다.
type: docs
weight: 144
url: /ko/system.drawing/texturebrush/multiplytransform/
---
## TextureBrush::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) 메서드


지정된 행렬에 의해 현재 객체의 변환 행렬을 곱합니다.

```cpp
void System::Drawing::TextureBrush::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 현재 객체의 변환 행렬을 곱하는 행렬 |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | 작업의 순서를 지정합니다. |

## 참고

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Matrix](../../../system.drawing.drawing2d/matrix/)
* 클래스 [TextureBrush](../)
* 네임스페이스 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)