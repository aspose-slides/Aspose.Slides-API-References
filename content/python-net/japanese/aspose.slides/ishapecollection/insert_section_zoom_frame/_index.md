---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
新しい Section Zoom フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

### Returns

新しく作成された [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe)。

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Section Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい Section Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Section Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Section Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Section Zoom フレームの高さ（ポイント単位）。 |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | Section Zoom フレームが参照する [`ISection`](/slides/python-net/ja/aspose.slides/isection);<br/><br/>            このプレゼンテーションに属し、少なくとも 1 枚のスライドを含む必要があります。 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたセクションが現在のプレゼンテーションに属していない場合、またはスライドが含まれていない場合にスローされます。 |

## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
事前定義された画像を持つ新しい Section Zoom フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

### Returns

新しく作成された [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe)。

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Section Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい Section Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Section Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Section Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Section Zoom フレームの高さ（ポイント単位）。 |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | Section Zoom フレームが参照する [`ISection`](/slides/python-net/ja/aspose.slides/isection);<br/><br/>            このプレゼンテーションに属し、少なくとも 1 枚のスライドを含む必要があります。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | Section Zoom フレーム内に表示する画像。 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたセクションが現在のプレゼンテーションに属していない場合、またはスライドが含まれていない場合にスローされます。 |

### See Also
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`ISection`](/slides/python-net/ja/aspose.slides/isection)
* クラス [`ISectionZoomFrame`](/slides/python-net/ja/aspose.slides/isectionzoomframe)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)