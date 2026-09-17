---
title: add_summary_zoom_section method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
新しい Summary Zoom Section オブジェクトを作成し、コレクションに追加します

### 戻り値

追加された [`ISummaryZoomFrame`](/slides/python-net/ja/aspose.slides/isummaryzoomframe) 要素



```python
def add_summary_zoom_section(self, section):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | 新しい Summary Zoom Section 要素 [`ISection`](/slides/python-net/ja/aspose.slides/isection) 用のセクション |

### 備考

このセクションの要素がすでにコレクションに存在する場合、既存の要素が返されます。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 参照されたセクションが現在のプレゼンテーションに属していないか、スライドが含まれていません。 |



### 参照
* クラス [`ISection`](/slides/python-net/ja/aspose.slides/isection)
* クラス [`ISummaryZoomFrame`](/slides/python-net/ja/aspose.slides/isummaryzoomframe)
* クラス [`ISummaryZoomSection`](/slides/python-net/ja/aspose.slides/isummaryzoomsection)
* クラス [`SummaryZoomSectionCollection`](/slides/python-net/ja/aspose.slides/summaryzoomsectioncollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)