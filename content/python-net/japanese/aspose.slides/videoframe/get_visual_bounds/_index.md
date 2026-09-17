---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。

### 戻り値

**aspose.slides.RectangleF** はスライド座標系でシェイプの視覚的境界を表す
             。




```python
def get_visual_bounds(self):
    ...
```


### 備考

返された矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの
             軸揃え境界を表します

これらの境界は、シェイプのモデル境界と異なる場合があります
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             そして、レンダリングされたコンテンツがスライドの原点を超えて拡張されている場合、負の座標を含むことがあります。

視覚的境界は、次のようなレンダリング関連の側面を考慮します
             変換（例: 回転）、ストローク幅とジョイン、
             テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果、
             これらはシェイプの最終的なレンダリング外観に影響を与えます。

返された境界はスライド矩形にクリップされません。

### 参照
* クラス [`VideoFrame`](/slides/python-net/ja/aspose.slides/videoframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)