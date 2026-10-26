---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/summaryzoomsection/get_image/
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

ShapeThumbnailBounds.Appearance が使用され、シェイプに表示要素がない場合は、シェイプのサムネイルまたは None を返します。



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | シェイプサムネイルの境界タイプ。 |
| scale_x | **float** | Xスケール |
| scale_y | **float** | Yスケール |



### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙型 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* クラス [`SummaryZoomSection`](/slides/python-net/ja/aspose.slides/summaryzoomsection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)