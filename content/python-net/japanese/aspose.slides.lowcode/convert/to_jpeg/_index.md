---
title: to_jpeg method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
入力のプレゼンテーションを JPEG 形式の画像セットに変換します。  
            出力ファイル名が "myPath/myFilename.jpeg" と指定された場合、結果は "myPath/myFilename_N.jpeg" ファイルのセットとして保存されます。N はスライド番号です。


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) | 入力プレゼンテーション。 |
| output_file_name | **str** | 出力ファイル名。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
入力のプレゼンテーションを JPEG 形式の画像セットに変換します。  
            出力ファイル名が "myPath/myFilename.jpeg" と指定された場合、結果は "myPath/myFilename_N.jpeg" ファイルのセットとして保存されます。N はスライド番号です。


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) | 入力プレゼンテーション |
| output_file_name | **str** | 出力ファイル名。 |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 生成される各画像のサイズ。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
入力のプレゼンテーションを JPEG 形式の画像セットに変換します。  
            出力ファイル名が "myPath/myFilename.jpeg" と指定された場合、結果は "myPath/myFilename_N.jpeg" ファイルのセットとして保存されます。N はスライド番号です。


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) | 入力プレゼンテーション。 |
| output_file_name | **str** | 出力ファイル名。 |
| scale | **float** | 元のスライドサイズに対する出力画像のスケーリング係数。 |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### 参照
* クラス [`Convert`](/slides/python-net/ja/aspose.slides.lowcode/convert)
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* クラス [`Size`](/slides/python-net/ja/aspose.slides/size)
* モジュール [`aspose.slides.lowcode`](/slides/python-net/ja/aspose.slides.lowcode)
* ライブラリ [`Aspose.Slides`](/slides/python-net)