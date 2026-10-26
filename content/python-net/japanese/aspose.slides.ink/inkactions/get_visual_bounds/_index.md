---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。

### 返り値

[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) は、シェイプの視覚的境界をスライド座標で表します。



```python
def get_visual_bounds(self):
    ...
```


### 備考

             返された矩形は、レンダリング中にシェイプが生成したすべてのコンテンツの軸に平行な境界を、スライド座標空間で表します。
            
             これらの境界は、シェイプのモデル境界（[`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x)、[`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y)、[`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width)、[`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)）と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えて拡張している場合、負の座標を含むことがあります。
            
             視覚的境界は、変換（例: 回転）、ストローク幅と結合、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果など、レンダリングに関連する側面を考慮します。
            
             返された境界はスライド矩形でクリップされません。



### 参照
* クラス [`InkActions`](/slides/python-net/ja/aspose.slides.ink/inkactions)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides.ink`](/slides/python-net/ja/aspose.slides.ink)
* ライブラリ [`Aspose.Slides`](/slides/python-net)