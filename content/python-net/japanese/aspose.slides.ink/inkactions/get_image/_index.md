---
title: get_image method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
シェイプのサムネイルを返します。
            ShapeThumbnailBounds.Shape シェイプサムネイルの境界タイプがデフォルトで使用されます。

### 戻り値

シェイプサムネイル。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 戻り値

ShapeThumbnailBounds.Appearance が使用され、シェイプに表示要素がない場合は、シェイプサムネイルまたは None が返されます。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | シェイプサムネイルの境界タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参考
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`InkActions`](/slides/python-net/ja/aspose.slides.ink/inkactions)
* 列挙体 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides.ink`](/slides/python-net/ja/aspose.slides.ink)
* ライブラリ [`Aspose.Slides`](/slides/python-net)