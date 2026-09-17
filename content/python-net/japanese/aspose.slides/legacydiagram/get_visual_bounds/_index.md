---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
シェイプの描画されたコンテンツから計算されたビジュアル境界を取得します。

### 戻り値

スライド座標系でシェイプのビジュアル境界を表す **aspose.slides.RectangleF** です。

```python
def get_visual_bounds(self):
    ...
```

### 備考

返される矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸に平行な境界を表します。

これらの境界はシェイプのモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えて拡張している場合、負の座標を含むことがあります。

ビジュアル境界は、変換（例: 回転）、ストローク幅と結合、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他シェイプの最終的なレンダリング外観に影響を与えるレイアウト効果など、レンダリングに関連する側面を考慮に入れます。

返される境界はスライド矩形にクリップされません。

### 参照
* クラス [`LegacyDiagram`](/slides/python-net/ja/aspose.slides/legacydiagram)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)