---
title: add_audio method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
別のプレゼンテーションからオーディオ ファイルのコピーを追加します。

### 戻り値

追加されたオーディオ。

```python
def add_audio(self, audio):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) | ソース オーディオ。 |

## add_audio(self, stream) {#iorawiobase}
ストリームからオーディオを作成し、プレゼンテーションに追加します。

### 戻り値

追加されたオーディオ。

```python
def add_audio(self, stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | オーディオを追加するストリーム。 |

## add_audio(self, audio_data) {#bytes}
バイト配列からオーディオを作成し、プレゼンテーションに追加します。

### 戻り値

追加されたオーディオ。

```python
def add_audio(self, audio_data):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| audio_data | **bytes** | オーディオ バイト列。 |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
ストリームからオーディオを作成し、プレゼンテーションに追加します。

### 戻り値

追加されたオーディオ。

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | ビデオ オーディオを追加するストリーム。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ja/aspose.slides/loadingstreambehavior) | ストリームに適用される動作。 |

### 参照
* クラス [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)
* クラス [`IAudioCollection`](/slides/python-net/ja/aspose.slides/iaudiocollection)
* 列挙型 [`LoadingStreamBehavior`](/slides/python-net/ja/aspose.slides/loadingstreambehavior)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)