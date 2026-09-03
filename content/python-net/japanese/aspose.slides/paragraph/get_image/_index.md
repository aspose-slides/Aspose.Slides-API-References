---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
段落の画像を返します。

### 戻り値
レンダリングされた段落を含む画像、または **None** 
             親コレクション内に段落が見つからない場合、 有効なレンダリング境界がない場合、 
             画像のレンダリング中にエラーが発生した場合に返されます。

```python
def get_image(self):
    ...
```

## get_image {#float-float}
指定されたスケールで段落の画像を返します。

### 戻り値
レンダリングされた段落を含む画像、または **None** 
             親コレクション内に段落が見つからない場合、 有効なレンダリング境界がない場合、 
             画像のレンダリング中にエラーが発生した場合に返されます。

```python
def get_image(self, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| scale_x | **float** | 段落画像に適用される水平スケール係数。 |
| scale_y | **float** | 段落画像に適用される垂直スケール係数。 |

### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`Paragraph`](/slides/python-net/ja/aspose.slides/paragraph)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)