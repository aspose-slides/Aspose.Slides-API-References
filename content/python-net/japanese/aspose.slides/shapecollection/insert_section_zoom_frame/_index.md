---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
新しい Section Zoom フレームを作成し、指定されたインデックスで shape コレクションに挿入します。

### 戻り値

新しく作成された [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | Section Zoom フレームを挿入するゼロベースのインデックスです。 |
| x | **float** | 新しい Section Zoom フレームの x 座標（ポイント単位）です。 |
| y | **float** | 新しい Section Zoom フレームの y 座標（ポイント単位）です。 |
| width | **float** | 新しい Section Zoom フレームの幅（ポイント単位）です。 |
| height | **float** | 新しい Section Zoom フレームの高さ（ポイント単位）です。 |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | Section Zoom フレームによって参照される [`ISection`](/slides/python-net/ja/aspose.slides/isection);<br/><br/>            このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたセクションが現在のプレゼンテーションに属していない場合、またはスライドが含まれていない場合にスローされます。 |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
事前に定義された画像を持つ新しい Section Zoom フレームを作成し、指定されたインデックスで shape コレクションに挿入します。

### 戻り値

新しく作成された [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | Section Zoom フレームを挿入するゼロベースのインデックスです。 |
| x | **float** | 新しい Section Zoom フレームの x座標（ポイント単位）です。 |
| y | **float** | 新しい Section Zoom フレームの y座標（ポイント単位）です。 |
| width | **float** | 新しい Section Zoom フレームの幅（ポイント単位）です。 |
| height | **float** | 新しい Section Zoom フレームの高さ（ポイント単位）です。 |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | Section Zoom フレームによって参照される [`ISection`](/slides/python-net/ja/aspose.slides/isection);<br/><br/>            このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | Section Zoom フレーム内に表示する画像です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたセクションが現在のプレゼンテーションに属していない場合、またはスライドが含まれていない場合にスローされます。 |



### 参照
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`ISection`](/slides/python-net/ja/aspose.slides/isection)
* クラス [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)