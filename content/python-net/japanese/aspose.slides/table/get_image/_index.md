---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
シェイプのサムネイルを返します。
            既定では ShapeThumbnailBounds.Shape がシェイプのサムネイル境界タイプとして使用されます。

### 戻り値

シェイプのサムネイル。



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 戻り値

ShapeThumbnailBounds.Appearance が使用され、シェイプに表示可能な要素がない場合は、シェイプのサムネイルまたは None を返します。



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | シェイプのサムネイル境界タイプです。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |



### 参照
* class [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* class [`Table`](/slides/python-net/ja/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)