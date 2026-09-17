---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe)。



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しい Section Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Section Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Section Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Section Zoom フレームの高さ（ポイント単位）。 |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | Section Zoom フレームが参照する [`ISection`](/slides/python-net/ja/aspose.slides/isection); このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたセクションが現在のプレゼンテーションに属していない、またはスライドが含まれていない場合にスローされます。 |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
事前定義された画像を使用した新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe)。



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しい Section Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Section Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Section Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Section Zoom フレームの高さ（ポイント単位）。 |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | Section Zoom フレームが参照する [`ISection`](/slides/python-net/ja/aspose.slides/isection); このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | Section Zoom フレーム内に表示する [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたセクションが現在のプレゼンテーションに属していない、またはスライドが含まれていない場合にスローされます。 |



### 関連項目
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`ISection`](/slides/python-net/ja/aspose.slides/isection)
* クラス [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)