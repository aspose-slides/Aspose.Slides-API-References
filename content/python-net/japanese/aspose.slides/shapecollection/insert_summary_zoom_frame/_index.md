---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
新しい Summary Zoom フレームを作成し、指定されたインデックスで shape コレクションに挿入します。

### 戻り値

新しく作成された [`ISummaryZoomFrame`](/slides/python-net/ja/aspose.slides/isummaryzoomframe)。

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | Summary Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい Summary Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Summary Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Summary Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Summary Zoom フレームの高さ（ポイント単位）。 |

### 備考

このメソッドは、プレゼンテーション内のすべてのセクションのサマリーリンクを集約する Summary Zoom フレームを作成します。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | プレゼンテーションにセクションが含まれていない場合、または対象スライドがいずれのセクションにも属していない場合にスローされます。 |

### 参照
* クラス [`ISummaryZoomFrame`](/slides/python-net/ja/aspose.slides/isummaryzoomframe)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)