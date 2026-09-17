---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
シェイプの描画されたコンテンツから計算されたビジュアル境界を取得します。

### 戻り値

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### 備考

返される矩形は、スライド座標空間での描画時にシェイプが生成するすべてのコンテンツの軸に平行な境界を表します。
            
これらの境界はシェイプのモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、描画されたコンテンツがスライドの原点を超えていると負の座標を含むことがあります。
            
ビジュアル境界は、変換（例: 回転）、ストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、およびシェイプの最終的な描画外観に影響を与えるその他のレイアウト効果など、レンダリングに関連する側面を考慮します。
            
返される境界はスライド矩形にクリップされません。



### 参照
* class [`SectionZoomFrame`](/slides/python-net/ja/aspose.slides/sectionzoomframe)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)