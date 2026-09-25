---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
形状のレンダリング済みコンテンツから計算されたビジュアル境界を取得します。

### Returns
### 戻り値

スライド座標系で形状のビジュアル境界を表す [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) です。

```python
def get_visual_bounds(self):
    ...
```

### Remarks
### 備考

返された矩形は、スライド座標空間でレンダリング時に形状が生成したすべてのコンテンツの軸平行境界を表します。

これらの境界は、形状のモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えている場合は負の座標を含むことがあります。

ビジュアル境界は、変換（例: 回転）、ストロークの幅と結合、テキストのレイアウトとオーバーフロー、SmartArt のジオメトリ、その他最終的なレンダリング外観に影響を与えるレイアウト効果など、レンダリングに関連する側面を考慮します。

返された境界はスライド矩形にクリップされません。

### See Also
### 参照
* クラス [`SectionZoomFrame`](/slides/python-net/ja/aspose.slides/sectionzoomframe)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)