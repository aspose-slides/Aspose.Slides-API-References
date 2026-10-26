---
title: replace_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ppimage/replace_image/
weight: 10
---
## replace_image(self, new_image_data) {#bytes}
画像データを置き換えます。
新しい画像のデータ。newImageData パラメーターが None の場合。

```python
def replace_image(self, new_image_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| new_image_data | **bytes** |  |

## replace_image(self, new_image) {#iimage}
画像データを置き換えます。注意: Image がメタファイルの場合、ラスター化されます。代わりに ReplaceImage(byte[]) を使用してください。
新しい画像。newImage パラメーターが None の場合。

```python
def replace_image(self, new_image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| new_image | [`IImage`](/slides/python-net/ja/aspose.slides/iimage) |  |

## replace_image(self, new_image) {#ippimage}
画像データを置き換えます。
新しい IPPImage。newImage パラメーターが None の場合。

```python
def replace_image(self, new_image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| new_image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) |  |

### See Also
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`PPImage`](/slides/python-net/ja/aspose.slides/ppimage)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)