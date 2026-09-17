---
title: get_visual_bounds method
second_title: Aspose.Slides Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。

### 戻り値

A **aspose.slides.RectangleF** は、スライド座標系におけるシェイプの視覚的境界を表します。
             
```python
def get_visual_bounds(self):
    ...
```


### 備考
返される矩形は、スライド座標空間でのレンダリング時にシェイプによって生成されたすべてのコンテンツの
             軸に平行な境界を表します。

これらの境界は、シェイプのモデル境界と異なる場合があります
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             そして、レンダリングされたコンテンツが拡張した場合、負の座標を含むことがあります
             スライドの原点を超える場合。

視覚的境界は、レンダリング関連の側面を考慮します（例として
             変換（例：回転）、ストローク幅とジョイン、テキストのレイアウトとオーバーフロー、SmartArtジオメトリ、その他のレイアウト効果、形状の最終的なレンダリング外観に影響を与えるものです）。

返された境界はスライド矩形にクリップされません。

### 参照
* クラス [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)