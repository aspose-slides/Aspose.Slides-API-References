---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
形状のサムネイルを返します。
デフォルトでは ShapeThumbnailBounds.Shape 形状サムネイル境界タイプが使用されます。

### 戻り値

形状サムネイル。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
形状のサムネイルを返します。

### 戻り値

Shape thumbnail または ShapeThumbnailBounds.Appearance が使用され、形状に表示要素がない場合は None が返されます。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | Shape thumbnail 境界タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参照
* クラス [`Connector`](/slides/python-net/ja/aspose.slides/connector)
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙体 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)