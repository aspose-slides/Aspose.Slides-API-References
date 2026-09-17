---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
シェイプの描画されたコンテンツから計算された視覚的境界を取得します。

### 戻り値

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### 備考

The returned rectangle represents the axis-aligned bounds of all content
             返された矩形は、すべてのコンテンツの軸に平行な境界を表します
            produced by the shape during rendering in slide coordinate space.
             シェイプがスライド座標空間でレンダリング中に生成したものです。

             
             These bounds may differ from the shape's model bounds
             これらの境界はシェイプのモデル境界と異なる場合があります
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             レンダリングされたコンテンツがスライドの原点を超える場合、負の座標を含むことがあります
             beyond the slide origin.
             スライドの原点を超えている場合。

             
             The visual bounds take into account rendering-related aspects such as
             視覚的境界は、次のようなレンダリングに関連する要素を考慮します
             transformations (for example, rotation), stroke width and joins,
             変換（例: 回転）、ストロークの幅と結合、
             text layout and overflow, SmartArt geometry, and other layout effects
             テキストのレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果
             that influence the final rendered appearance of the shape.
             これらはシェイプの最終的なレンダリング外観に影響を与えます。

             
             The returned bounds are not clipped to the slide rectangle.
             返された境界はスライド矩形にクリップされません。

### 参照
* クラス [`SmartArtShape`](/slides/python-net/ja/aspose.slides.smartart/smartartshape)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)