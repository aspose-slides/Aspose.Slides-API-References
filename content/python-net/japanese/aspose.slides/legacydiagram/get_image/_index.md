---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/legacydiagram/get_image/
weight: 50
---
## get_image(self) {#}
シェイプのサムネイルを返します。  
デフォルトでは ShapeThumbnailBounds.Shape シェイプサムネイル境界タイプが使用されます。

### 戻り値

Shape サムネイル。



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 戻り値

ShapeThumbnailBounds.Appearance が使用され、Shape に可視要素がない場合は、Shape サムネイルまたは None が返されます。



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | Shape サムネイル境界タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |



### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`LegacyDiagram`](/slides/python-net/ja/aspose.slides/legacydiagram)
* 列挙型 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)