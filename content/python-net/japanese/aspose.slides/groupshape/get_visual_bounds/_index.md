---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
描画されたコンテンツから計算されたシェイプのビジュアル境界を取得します。

### 戻り値

シェイプのビジュアル境界をスライド座標で表す **aspose.slides.RectangleF**。

```python
def get_visual_bounds(self):
    ...
```

### 備考

返される矩形は、スライド座標空間でのレンダリング中にシェイプによって生成されたすべてのコンテンツの軸に平行な境界を表します。

これらの境界はシェイプのモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えると負の座標を含むことがあります。

ビジュアル境界は、変換（例: 回転）やストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他シェイプの最終的なレンダリング外観に影響するレイアウト効果など、レンダリングに関連する要素を考慮します。

返される境界はスライド矩形にクリップされません。

### 参照
* クラス [`GroupShape`](/slides/python-net/ja/aspose.slides/groupshape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)