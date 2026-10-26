---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。

### 戻り値

[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) はシェイプの視覚的境界をスライド座標系で表します
             。

```python
def get_visual_bounds(self):
    ...
```


### 備考

返された矩形は、レンダリング中にシェイプが生成したすべてのコンテンツの
             軸に平行な境界をスライド座標空間で表します。
            
             これらの境界はシェイプのモデル境界
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             と異なる場合があり、レンダリングされたコンテンツが
             スライドの原点を超えると負の座標を含むことがあります。
            
             視覚的境界は、変換（例: 回転）、ストローク幅とジョイン、
             テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、
             その他のレイアウト効果など、最終的な描画外観に影響する
             レンダリング関連の側面を考慮します。
            
             返された境界はスライド矩形にクリップされません。



### 関連項目
* クラス [`SmartArt`](/slides/python-net/ja/aspose.slides.smartart/smartart)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)