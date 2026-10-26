---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
シェイプのサムネイルを返します。
            ShapeThumbnailBounds.Shape shape thumbnail bounds type はデフォルトで使用されます。

### 戻り値

シェイプのサムネイル。



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 戻り値

シェイプのサムネイル または、ShapeThumbnailBounds.Appearance が使用され、シェイプに表示要素がない場合は None が返されます。



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | シェイプのサムネイル境界タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |



### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* クラス [`ZoomFrame`](/slides/python-net/ja/aspose.slides/zoomframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)