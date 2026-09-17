---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。

### 戻り値

A **aspose.slides.RectangleF** が、スライド座標系でシェイプの視覚的境界を表します。
             
```python
def get_visual_bounds(self):
    ...
```


### 備考

返された矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸に平行な境界を表します。

これらの境界はシェイプのモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えている場合、負の座標を含むことがあります。

視覚的境界は、変換（例: 回転）、ストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、そしてシェイプの最終的なレンダリング外観に影響を与えるその他のレイアウト効果など、レンダリング関連の要素を考慮します。

返された境界はスライド矩形にクリップされません。

### 参照
* クラス [`Table`](/slides/python-net/ja/aspose.slides/table)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)