---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
シェイプのサムネイルを返します。  
デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。

### 戻り値

シェイプサムネイル。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 戻り値

ShapeThumbnailBounds.Appearance が使用され、シェイプに可視要素がない場合は、シェイプサムネイルまたは None を返します。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | シェイプサムネイル境界タイプ。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`Ink`](/slides/python-net/ja/aspose.slides.ink/ink)
* 列挙型 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides.ink`](/slides/python-net/ja/aspose.slides.ink)
* ライブラリ [`Aspose.Slides`](/slides/python-net)