---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
シェイプサムネイルを返します。  
デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。

### 戻り値

シェイプサムネイル。



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプサムネイルを返します。

### 戻り値

ShapeThumbnailBounds.Appearance が使用され、シェイプに表示要素がない場合は、シェイプサムネイルまたは None を返します。



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | シェイプサムネイル境界タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |



### 関連項目
* class [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* class [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)