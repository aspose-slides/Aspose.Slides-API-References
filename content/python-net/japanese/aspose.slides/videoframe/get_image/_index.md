---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
シェイプのサムネイルを返します。  
ShapeThumbnailBounds.Shape の形状サムネイル境界タイプがデフォルトで使用されます。

### 戻り値

Shape サムネイル。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 戻り値

Shape サムネイル、または ShapeThumbnailBounds.Appearance が使用され、シェイプに可視要素がない場合は None が返されます。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| パラメータ | タイプ | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | Shape サムネイル境界タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙型 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* クラス [`VideoFrame`](/slides/python-net/ja/aspose.slides/videoframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)