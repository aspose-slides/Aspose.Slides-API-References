---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の Graphics オブジェクトのワールド変換行列を指定された行列で乗算します。
type: docs
weight: 872
url: /ja/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) メソッド

指定された行列で現在の [Graphics](../) オブジェクトのワールド変換行列を乗算します。

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 現在の [Graphics](../) オブジェクトのワールド変換行列に乗算する行列 |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | 乗算順序 |

## 参照

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../../../system.drawing.drawing2d/matrix/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)