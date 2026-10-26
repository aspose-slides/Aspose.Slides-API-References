---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
シェイプのサイズと指定された解像度に基づいてサイズを縮小することで画像を圧縮します。オプションで、クロップされた領域を削除することもできます。

### 戻り値

画像が正常に圧縮されたかどうかを示す **bool**。画像がサイズ変更またはクロップされた場合は **True**、それ以外の場合は **False** を返します。

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | true の場合、メソッドは画像のクロップ領域を削除し、サイズをさらに削減する可能性があります。 |
| resolution | [`PicturesCompression`](/slides/python-net/ja/aspose.slides.export/picturescompression) | 圧縮の対象となる解像度で、[`PicturesCompression`](/slides/python-net/ja/aspose.slides.export/picturescompression) 列挙体の値として指定されます。 |

### 備考

このメソッドは、PowerPoint の「Picture Format -> Compress Pictures」機能と同様に、画像のサイズと解像度を変更します。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 解像度が有効な値でない場合にスローされます。 |

## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
シェイプのサイズと指定された解像度に基づいてサイズを縮小することで画像を圧縮します。オプションで、クロップされた領域を削除することもできます。

### 戻り値

画像が正常に圧縮されたかどうかを示す **bool**。画像がサイズ変更またはクロップされた場合は **True**、それ以外の場合は **False** を返します。

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | true の場合、メソッドは画像のクロップ領域を削除し、サイズをさらに削減する可能性があります。 |
| resolution | **float** | DPI 単位の対象解像度。この値は正の数である必要があり、画像のリサイズ方法を定義します。 |

### 備考

このメソッドは、PowerPoint の「Picture Format -> Compress Pictures」機能と同様に、画像のサイズと解像度を変更します。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 解像度が正の値でない場合にスローされます。 |

### 参照
* クラス [`IPictureFillFormat`](/slides/python-net/ja/aspose.slides/ipicturefillformat)
* 列挙体 [`PicturesCompression`](/slides/python-net/ja/aspose.slides.export/picturescompression)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)