---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。

### 戻り値

スライド座標系でシェイプの視覚的境界を表す[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)です。

```python
def get_visual_bounds(self):
    ...
```

### 補足

返された矩形は、スライド座標空間でレンダリング中にシェイプが生成したすべてのコンテンツの軸整列境界を表します。

これらの境界はシェイプのモデル境界（[`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)）と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えると負の座標を含むことがあります。

視覚的境界は、変形（例: 回転）やストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他シェイプの最終的なレンダリング外観に影響を与えるレイアウト効果など、レンダリングに関連する側面を考慮します。

返された境界はスライド矩形にクリップされません。

### 参照
* クラス [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)