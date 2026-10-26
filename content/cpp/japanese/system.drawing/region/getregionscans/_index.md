---
title: GetRegionScans()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された行列変換が適用された後、この Region を近似する RectangleF 構造体の配列を返します。
type: docs
weight: 27
url: /ja/system.drawing/region/getregionscans/
---
## Region::GetRegionScans(const SharedPtr\<Drawing2D::Matrix\>\&) const メソッド

指定された行列変換が適用された後、この [Region](../) を近似する [RectangleF](../../rectanglef/) 構造体の配列を返します。

```cpp
ArrayPtr<RectangleF> System::Drawing::Region::GetRegionScans(const SharedPtr<Drawing2D::Matrix> &matrix) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 領域に適用する幾何変換を表す Matrix |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RectangleF](../../rectanglef/)
* クラス [Matrix](../../../system.drawing.drawing2d/matrix/)
* クラス [Region](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)