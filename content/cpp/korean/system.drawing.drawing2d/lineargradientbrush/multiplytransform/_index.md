---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 행렬을 사용하여 현재 객체의 변환 행렬을 곱합니다.
type: docs
weight: 27
url: /ko/system.drawing.drawing2d/lineargradientbrush/multiplytransform/
---
## LinearGradientBrush::MultiplyTransform(const SharedPtr\<Matrix\>\&, MatrixOrder) 메서드

현재 객체의 변환 행렬에 지정된 행렬을 곱합니다.

```cpp
void System::Drawing::Drawing2D::LinearGradientBrush::MultiplyTransform(const SharedPtr<Matrix> &matrix, MatrixOrder order=MatrixOrder::Prepend)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Matrix](../../matrix/)\>\& | 현재 객체의 변환 행렬에 곱해지는 행렬 |
| order | [MatrixOrder](../../matrixorder/) | 작업의 순서를 지정합니다 |

## 참고

* 열거형 [MatrixOrder](../../matrixorder/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Matrix](../../matrix/)
* 클래스 [LinearGradientBrush](../)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)