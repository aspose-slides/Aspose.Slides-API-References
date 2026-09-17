---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
シェイプのサムネイルを返します。
            ShapeThumbnailBounds.Shapeはデフォルトで使用されるシェイプサムネイル境界タイプです。

### 戻り値

シェイプサムネイル。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
シェイプのサムネイルを返します。

### 戻り値

シェイプサムネイル、または ShapeThumbnailBounds.Appearance が使用され、シェイプに可視要素がない場合は None を返します。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds) | シェイプサムネイル境界タイプです。 |
| scale_x | **float** | X スケール |
| scale_y | **float** | Y スケール |

### 参照
* クラス [`AudioFrame`](/slides/python-net/ja/aspose.slides/audioframe)
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙 [`ShapeThumbnailBounds`](/slides/python-net/ja/aspose.slides/shapethumbnailbounds)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)