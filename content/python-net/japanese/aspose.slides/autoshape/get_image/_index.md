---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
シェイプ サムネイルを返します。  
ShapeThumbnailBounds.Shape shape thumbnail bounds type はデフォルトで使用されます。

### 戻り値

Shape サムネイル。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプ サムネイルを返します。

### 戻り値

Shape サムネイル、または ShapeThumbnailBounds.Appearance が使用され、図形に可視要素がない場合は None を返します。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | Shape サムネイル bounds タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参照
* クラス [`AutoShape`](/slides/python-net/ja/aspose.slides/autoshape)
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)