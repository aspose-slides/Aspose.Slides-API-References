---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトの変換行列を指定された行列で乗算します。
type: docs
weight: 144
url: /ja/system.drawing/texturebrush/multiplytransform/
---
## TextureBrush::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) メソッド

現在のオブジェクトの変換行列を指定された行列で乗算します。

```cpp
void System::Drawing::TextureBrush::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 現在のオブジェクトの変換行列が乗算される行列 |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | 操作の順序を指定します |

## 参照

* 列挙体 [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Matrix](../../../system.drawing.drawing2d/matrix/)
* クラス [TextureBrush](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)