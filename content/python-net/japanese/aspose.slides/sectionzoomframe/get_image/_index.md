---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/sectionzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
shape のサムネイルを返します。  
デフォルトでは ShapeThumbnailBounds.Shape の shape thumbnail bounds タイプが使用されます。

### 戻り値

Shape のサムネイル。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
shape のサムネイルを返します。

### 戻り値

Shape のサムネイル、または ShapeThumbnailBounds.Appearance が使用され、シェイプに可視要素がない場合は None が返されます。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds のタイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`SectionZoomFrame`](/slides/python-net/ja/aspose.slides/sectionzoomframe)
* 列挙型 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)