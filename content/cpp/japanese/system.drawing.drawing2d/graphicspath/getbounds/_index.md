---
title: GetBounds()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された行列で変換された現在のオブジェクトが表すパスを囲む矩形を表す RectangleF オブジェクトを返します。
type: docs
weight: 339
url: /ja/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const メソッド

[RectangleF](../../../system.drawing/rectanglef/) オブジェクトを返します。このオブジェクトは、指定された行列で変換された現在のオブジェクトが表すパスを囲む矩形を表します。

```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 変換行列 |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../../system.drawing/pen/)\>\& | バウンディング矩形を計算するための [Pen](../../../system.drawing/pen/) 。 |

## 関連項目

* typedef [MatrixPtr](../../matrixptr/)
* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [RectangleF](../../../system.drawing/rectanglef/)
* クラス [Pen](../../../system.drawing/pen/)
* クラス [GraphicsPath](../)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)