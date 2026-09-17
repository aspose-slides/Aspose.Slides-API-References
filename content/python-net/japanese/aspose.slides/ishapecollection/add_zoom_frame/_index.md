---
title: add_zoom_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
新しいズームフレームを作成し、シェイプコレクションの末尾に追加します。

### 戻り値

新しく作成された[`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe)。



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | 新しいズームフレームのX座標（ポイント単位）。 |
| y | **float** | 新しいズームフレームのY座標（ポイント単位）。 |
| width | **float** | 新しいズームフレームの幅（ポイント単位）。 |
| height | **float** | 新しいズームフレームの高さ（ポイント単位）。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | Zoomフレームが参照する[`ISlide`](/slides/python-net/ja/aspose.slides/islide);<br/><br/>            このプレゼンテーションに属している必要があります。 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたスライドが現在のプレゼンテーションに属していない場合にスローされます。 |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
新しいズームフレームを作成し、シェイプコレクションの末尾に追加します。

### 戻り値

新しく作成された[`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe)。



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | 新しいズームフレームのX座標（ポイント単位）。 |
| y | **float** | 新しいズームフレームのY座標（ポイント単位）。 |
| width | **float** | 新しいズームフレームの幅（ポイント単位）。 |
| height | **float** | 新しいズームフレームの高さ（ポイント単位）。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | Zoomフレームが参照する[`ISlide`](/slides/python-net/ja/aspose.slides/islide);<br/><br/>            このプレゼンテーションに属している必要があります。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | 参照されたスライド[`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)の画像。 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたスライドが現在のプレゼンテーションに属していない場合にスローされます。 |



### 関連項目
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)