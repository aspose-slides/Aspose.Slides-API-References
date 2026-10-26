---
title: add_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
新しい Summary Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された [`ISummaryZoomFrame`](/slides/python-net/ja/aspose.slides/isummaryzoomframe)。

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| x | **float** | 新しい Summary Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Summary Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Summary Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Summary Zoom フレームの高さ（ポイント単位）。 |

### 備考

このメソッドは、プレゼンテーション内のすべてのセクションのサマリー リンクを集約する Summary Zoom フレームを作成します。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | プレゼンテーションにセクションがない場合、または対象スライドがいずれのセクションにも属さない場合にスローされます。 |

### 参照
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* クラス [`ISummaryZoomFrame`](/slides/python-net/ja/aspose.slides/isummaryzoomframe)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)