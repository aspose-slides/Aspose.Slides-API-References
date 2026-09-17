---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
コレクションの末尾に WebVTT クローズドキャプションを追加します。

### 戻り値

追加された [`ICaptions`](/slides/python-net/ja/aspose.slides/icaptions) インスタンスです。



```python
def add(self, label, file_path):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| label | **str** | 閉じた字幕のラベル。 |
| file_path | **str** | WebVTT ファイルへのパス。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `file_path` が `None` の場合にスローされます。 |
| **RuntimeError(Proxy error(ArgumentException))** | `file_path` が空の場合にスローされます。 |


## add(self, label, stream) {#str-iorawiobase}
ストリームからコレクションの末尾に WebVTT クローズドキャプションを追加します。

### 戻り値

追加された [`ICaptions`](/slides/python-net/ja/aspose.slides/icaptions) インスタンスです。



```python
def add(self, label, stream):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| label | **str** | 閉じた字幕のラベル。 |
| stream | **io.RawIOBase** | WebVTT 形式のデータを含む入力ストリーム。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `stream` が `None` の場合にスローされます。 |
| **RuntimeError(Proxy error(ArgumentException))** | 入力データが WebVTT 形式でない場合にスローされます。 |



### 関連項目
* クラス [`ICaptions`](/slides/python-net/ja/aspose.slides/icaptions)
* クラス [`ICaptionsCollection`](/slides/python-net/ja/aspose.slides/icaptionscollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)