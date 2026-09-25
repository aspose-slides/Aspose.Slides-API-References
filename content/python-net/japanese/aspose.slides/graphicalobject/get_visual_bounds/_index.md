---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
シェイプのレンダリングされたコンテンツから計算されたビジュアル境界を取得します。

### 戻り値

[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) は、スライド座標系でシェイプのビジュアル境界を表す矩形です



```python
def get_visual_bounds(self):
    ...
```


### 備考

返される矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸に平行な境界を表します。

これらの境界はシェイプのモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えると負の座標を含むことがあります。

ビジュアル境界は、変換（例：回転）、ストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果など、最終的なレンダリング外観に影響を与えるレンダリング関連の側面を考慮します。

返された境界はスライド矩形にクリップされません。



### 関連項目
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)