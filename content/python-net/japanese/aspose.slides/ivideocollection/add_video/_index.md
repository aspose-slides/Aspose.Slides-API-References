---
title: add_video method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
別のプレゼンテーションからビデオファイルのコピーを追加します。

### 戻り値

追加されたビデオ。

```python
def add_video(self, video):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/ja/aspose.slides/ivideo) | ソースビデオ。 |

## add_video(self, video_data) {#bytes}
バイト配列からビデオを作成し、プレゼンテーションに追加します。

### 戻り値

追加されたビデオ。

```python
def add_video(self, video_data):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| video_data | **bytes** | ビデオのバイト。 |

## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
ストリームからビデオを作成し、プレゼンテーションに追加します。

### 戻り値

追加された [`IVideo`](/slides/python-net/ja/aspose.slides/ivideo)。

```python
def add_video(self, stream, loading_stream_behavior):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | ビデオファイルを追加するストリーム。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ja/aspose.slides/loadingstreambehavior) | ストリームに適用される動作。 |

### 参照
* クラス [`IVideo`](/slides/python-net/ja/aspose.slides/ivideo)
* クラス [`IVideoCollection`](/slides/python-net/ja/aspose.slides/ivideocollection)
* 列挙型 [`LoadingStreamBehavior`](/slides/python-net/ja/aspose.slides/loadingstreambehavior)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)