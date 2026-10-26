---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
シェイプのレンダリングされたコンテンツから計算された、シェイプの視覚的境界を取得します。

### 戻り値

[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)は、スライド座標系におけるシェイプの視覚的境界を表します
             スライド座標系で

```python
def get_visual_bounds(self):
    ...
```

### 備考
返された矩形は、すべてのコンテンツの軸揃えされた境界を表します
             シェイプがスライド座標空間でレンダリング中に生成したものです。

             これらの境界はシェイプのモデル境界
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えている場合、負の座標を含むことがあります。

             視覚的境界は、次のようなレンダリング関連の側面を考慮します
             変換（例: 回転）、ストローク幅とジョイン、 
             テキストレイアウトとオーバーフロー、SmartArt ジオメトリ、その他のレイアウト効果
             これらはシェイプの最終的なレンダリング外観に影響を与えます。

             返された境界はスライド矩形にクリップされません。

### 関連項目
* クラス [`AutoShape`](/slides/python-net/ja/aspose.slides/autoshape)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)