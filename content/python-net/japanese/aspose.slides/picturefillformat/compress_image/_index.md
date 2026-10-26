---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
形状のサイズと指定された解像度に基づいてサイズを縮小し、画像を圧縮します。オプションで、切り取られた領域を削除することもできます。

### Returns
**bool** は画像が正常に圧縮されたかどうかを示します。画像がサイズ変更または切り取りされた場合は **True**、それ以外の場合は **False** を返します。

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | true の場合、メソッドは画像の切り取られた領域を削除し、サイズをさらに縮小する可能性があります。 |
| resolution | [`PicturesCompression`](/slides/python-net/ja/aspose.slides.export/picturescompression) | 圧縮の対象解像度で、[`PicturesCompression`](/slides/python-net/ja/aspose.slides.export/picturescompression) 列挙体の値として指定されます。 |

### Remarks
このメソッドは、PowerPoint の「画像の書式設定 -> 画像の圧縮」機能と同様に画像のサイズと解像度を変更します。

### Exceptions
| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 解像度が有効な値でない場合にスローされます。 |

## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
形状のサイズと指定された解像度に基づいてサイズを縮小し、画像を圧縮します。オプションで、切り取られた領域を削除することもできます。

### Returns
**bool** は画像が正常に圧縮されたかどうかを示します。画像がサイズ変更または切り取りされた場合は **True**、それ以外の場合は **False** を返します。

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | true の場合、メソッドは画像の切り取られた領域を削除し、サイズをさらに縮小する可能性があります。 |
| resolution | **float** | DPI の対象解像度です。この値は正でなければならず、画像がどのようにサイズ変更されるかを定義します。 |

### Remarks
このメソッドは、PowerPoint の「画像の書式設定 -> 画像の圧縮」機能と同様に画像のサイズと解像度を変更します。

### Exceptions
| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 解像度が正の値でない場合にスローされます。 |

### See Also
* クラス [`PictureFillFormat`](/slides/python-net/ja/aspose.slides/picturefillformat)
* 列挙体 [`PicturesCompression`](/slides/python-net/ja/aspose.slides.export/picturescompression)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)