---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算されるシェイプのビジュアル境界を取得します。

### 戻り値

A [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) that represents the visual bounds of the shape
             スライド座標系で。

```python
def get_visual_bounds(self):
    ...
```


### 備考

返された矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸に平行な境界を表します。
             
These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
             
ビジュアル境界は、変換（例: 回転）やストローク幅と結合、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他シェイプの最終的なレンダリング外観に影響を与えるレイアウト効果など、レンダリングに関連する要素を考慮します。
             
返された境界はスライド矩形にクリップされません。



### 参照
* クラス [`Table`](/slides/python-net/ja/aspose.slides/table)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)