---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image(self) {#}
段落の画像を返します。

### Returns

An image containing the rendered paragraph, or **None**
             段落が親コレクション内に見つからない場合、または有効な
             レンダリング境界がない場合、あるいは画像のレンダリング中にエラーが発生した場合です。

```python
def get_image(self):
    ...
```

## get_image(self, scale_x, scale_y) {#float-float}
指定したスケールで段落の画像を返します。

### Returns

An image containing the rendered paragraph, or **None**
             段落が親コレクション内に見つからない場合、または有効な
             レンダリング境界がない場合、あるいは画像のレンダリング中にエラーが発生した場合です。

```python
def get_image(self, scale_x, scale_y):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| scale_x | **float** | 段落画像に適用される水平スケール係数です。 |
| scale_y | **float** | 段落画像に適用される垂直スケール係数です。 |

### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`IParagraph`](/slides/python-net/ja/aspose.slides/iparagraph)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)