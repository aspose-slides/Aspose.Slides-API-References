---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
シェイプのレンダリングされたコンテンツから計算されたビジュアル境界を取得します。

### 戻り値

[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) は、スライド座標系でシェイプのビジュアル境界を表します。

```python
def get_visual_bounds(self):
    ...
```

### 備考
The returned rectangle represents the axis-aligned bounds of all content
             シェイプがスライド座標空間でレンダリング中に生成した
These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             そして、レンダリングされたコンテンツが拡張した場合、負の座標を含むことがあります
             スライドの原点を超えて
The visual bounds take into account rendering-related aspects such as
             変換（例: 回転）、ストローク幅と結合、
             テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果
             これらはシェイプの最終的なレンダリング外観に影響します。
The returned bounds are not clipped to the slide rectangle。

### 関連項目
* クラス [`LegacyDiagram`](/slides/python-net/ja/aspose.slides/legacydiagram)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)