---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
新しいズーム フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

### Returns
新しく作成された [`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe)。

```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Zoom フレームの高さ（ポイント単位）。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | Zoom フレームが参照する [`ISlide`](/slides/python-net/ja/aspose.slides/islide)。 |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたスライドが現在のプレゼンテーションに属していない場合にスローされます。 |

## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
事前に定義された画像を使用して新しいズーム フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

### Returns
新しく作成された [`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe)。

```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Zoom フレームの高さ（ポイント単位）。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | Zoom フレームが参照する [`ISlide`](/slides/python-net/ja/aspose.slides/islide)。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | 参照されたスライド [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) の画像。 |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたスライドが現在のプレゼンテーションに属していない場合にスローされます。 |

### See Also
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`IZoomFrame`](/slides/python-net/ja/aspose.slides/izoomframe)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)