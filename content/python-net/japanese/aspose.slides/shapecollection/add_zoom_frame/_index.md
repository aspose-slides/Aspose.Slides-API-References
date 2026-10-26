---
title: add_zoom_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された[`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しい Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Zoom フレームの高さ（ポイント単位）。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | Zoom フレームが参照する[`ISlide`](/slides/python-net/ja/aspose.slides/islide)です；<br/><br/>            このプレゼンテーションに属している必要があります。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたスライドが現在のプレゼンテーションに属していない場合にスローされます。 |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された[`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しい Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Zoom フレームの高さ（ポイント単位）。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | Zoom フレームが参照する[`ISlide`](/slides/python-net/ja/aspose.slides/islide)です；<br/><br/>            このプレゼンテーションに属している必要があります。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | 参照されたスライド[`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)の画像です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたスライドが現在のプレゼンテーションに属していない場合にスローされます。 |



### 参照
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)