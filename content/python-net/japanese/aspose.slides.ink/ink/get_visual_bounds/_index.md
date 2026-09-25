---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
シェイプのレンダリングされたコンテンツから計算されたビジュアル境界を取得します。

### 戻り値

スライド座標系におけるシェイプのビジュアル境界を表す [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) です。



```python
def get_visual_bounds(self):
    ...
```


### 備考

返された矩形は、スライド座標空間でのレンダリング中にシェイプが生成したすべてのコンテンツの軸に平行な境界を表します。

これらの境界は、シェイプのモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えて拡張されると負の座標を含むことがあります。

ビジュアル境界は、変換（例として回転）、ストローク幅と結合、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、そしてシェイプの最終的なレンダリング外観に影響を与えるその他のレイアウト効果など、レンダリングに関連する側面を考慮します。

返された境界はスライド矩形にクリップされません。



### 参照
* クラス [`Ink`](/slides/python-net/ja/aspose.slides.ink/ink)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides.ink`](/slides/python-net/ja/aspose.slides.ink)
* ライブラリ [`Aspose.Slides`](/slides/python-net)