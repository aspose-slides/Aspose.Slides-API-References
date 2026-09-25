---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算されたシェイプのビジュアル境界を取得します。

### 戻り値

[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) は、スライド座標系でシェイプのビジュアル境界を表します。

```python
def get_visual_bounds(self):
    ...
```

### 備考

返された矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸整列境界を表します。

これらの境界は、シェイプのモデル境界
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             と異なる場合があり、レンダリングされたコンテンツが
             スライドの原点を超えている場合、負の座標を含むことがあります。

ビジュアル境界は、変換（例: 回転）、線幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他シェイプの最終的なレンダリング外観に影響を与えるレイアウト効果など、レンダリングに関連する側面を考慮します。

返された境界はスライド矩形にクリップされません。

### 参照
* クラス [`SmartArtShape`](/slides/python-net/ja/aspose.slides.smartart/smartartshape)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)