---
title: Hyperlink constructor
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
ハイパーリンクのインスタンスを作成します。


```python
def __init__(self, url):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| url | **str** | ハイパーリンクの URL。 |


## __init__(self, slide) {#islide}
特定のスライドを指すハイパーリンクのインスタンスを作成します。
            注意: 作成したハイパーリンクは同じプレゼンテーション内のオブジェクトに割り当てる必要があります。そうしないとリンクは NoAction として保存されます。


```python
def __init__(self, slide):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | 対象スライド。 |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
別のハイパーリンクをソースとして使用し、二次プロパティを上書きしたハイパーリンクのインスタンスを作成します。


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink) | ソースハイパーリンク |
| target_frame | **str** | 対象フレーム |
| tooltip | **str** | ツールチップテキスト |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### 参照
* クラス [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)