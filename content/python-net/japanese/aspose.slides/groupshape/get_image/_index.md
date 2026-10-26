---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
シェイプのサムネイルを返します。  
デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。

### 返り値

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 返り値

Shape thumbnail または、ShapeThumbnailBounds.Appearance が使用され、シェイプに表示要素がない場合は None を返します。



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | シェイプサムネイル境界タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |



### 参照
* クラス [`GroupShape`](/slides/python-net/ja/aspose.slides/groupshape)
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙型 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)