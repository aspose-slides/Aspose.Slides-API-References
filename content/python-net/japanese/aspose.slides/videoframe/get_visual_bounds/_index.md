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

シェイプの視覚的境界をスライド座標で表す [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) です
             。

```python
def get_visual_bounds(self):
    ...
```

### 備考

返される矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸整列境界を表します。
            
これらの境界はシェイプのモデル境界
（[`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)）とは異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えると負の座標を含むことがあります。
            
視覚的境界は、変換（例: 回転）、ストローク幅と結合、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果など、レンダリングに関係する側面を考慮します。
            
返された境界はスライド矩形でクリップされません。

### 参照
* クラス [`VideoFrame`](/slides/python-net/ja/aspose.slides/videoframe)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)