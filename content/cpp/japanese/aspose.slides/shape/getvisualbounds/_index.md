---
title: GetVisualBounds()
second_title: Aspose.Slides for C++ API リファレンス
description: レンダリングされたコンテンツから計算されたシェイプのビジュアル境界を取得します。
type: docs
weight: 677
url: /ja/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() メソッド

レンダリングされたコンテンツから計算されたシェイプのビジュアル境界を取得します。

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### 戻り値

[System::Drawing::RectangleF](../../../system.drawing/rectanglef/) は、スライド座標系におけるシェイプのビジュアル境界を表すものです。

## 備考

返される矩形は、スライド座標空間でのレンダリング時にシェイプによって生成されたすべてのコンテンツの軸に平行な境界を表します。

これらの境界は、シェイプのモデル境界 ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えている場合、負の座標を含むことがあります。

ビジュアル境界は、変換（例: 回転）やストローク幅・結合、テキストレイアウトとオーバーフロー、[SmartArt](../../../aspose.slides.smartart/) ジオメトリ、そしてシェイプの最終的なレンダリング外観に影響を与えるその他のレイアウト効果など、レンダリングに関する要素を考慮します。

返された境界はスライドの矩形でクリップされません。

## 参照

* クラス [RectangleF](../../../system.drawing/rectanglef/)
* クラス [Shape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)