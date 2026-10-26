---
title: get_image method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
シェイプのサムネイルを返します。
ShapeThumbnailBounds.Shape shape thumbnail bounds type がデフォルトで使用されます。

### 戻り値

シェイプのサムネイル。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 戻り値

Shape thumbnail または None は、ShapeThumbnailBounds.Appearance が使用され、シェイプに表示要素がない場合に返されます。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙型 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* クラス [`SmartArt`](/slides/python-net/ja/aspose.slides.smartart/smartart)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)