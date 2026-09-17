---
title: add_audio method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
別のプレゼンテーションからオーディオファイルのコピーを追加します。

### 戻り値

追加されたオーディオ。

```python
def add_audio(self, audio):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio) | ソースオーディオ。 |

## add_audio(self, stream) {#iorawiobase}
ストリームからプレゼンテーションにオーディオを作成して追加します。

### 戻り値

追加されたオーディオ。

```python
def add_audio(self, stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | オーディオを追加するストリーム。 |

## add_audio(self, audio_data) {#bytes}
バイト配列からプレゼンテーションにオーディオを作成して追加します。

### 戻り値

追加されたオーディオ。

```python
def add_audio(self, audio_data):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| audio_data | **bytes** | オーディオのバイト。 |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
ストリームからプレゼンテーションにオーディオを作成して追加します。

### 戻り値

追加されたオーディオ。

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | ビデオオーディオを追加するストリーム。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ja/aspose.slides/loadingstreambehavior) | ストリームに適用される動作。 |

### 参照
* クラス [`AudioCollection`](/slides/python-net/ja/aspose.slides/audiocollection)
* クラス [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)
* 列挙型 [`LoadingStreamBehavior`](/slides/python-net/ja/aspose.slides/loadingstreambehavior)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)