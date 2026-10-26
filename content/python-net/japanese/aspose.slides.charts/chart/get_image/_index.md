---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chart/get_image/
weight: 40
---
## get_image(self) {#}
shape thumbnail を返します。
            ShapeThumbnailBounds.Shape shape thumbnail bounds type がデフォルトで使用されます。

### 戻り値

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
shape thumbnail を返します。

### 戻り値

Shape thumbnail または ShapeThumbnailBounds.Appearance が使用され、シェイプに表示可能な要素がない場合は None を返します。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参照
* クラス [`Chart`](/slides/python-net/ja/aspose.slides.charts/chart)
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙型 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)