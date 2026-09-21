---
title: add_audio method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
從另一個簡報新增音訊檔案的副本。

### 返回值
已添加的音訊。

```python
def add_audio(self, audio):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio) | 原始音訊。 |

## add_audio(self, stream) {#iorawiobase}
從串流建立並添加音訊至簡報。

### 返回值
已添加的音訊。

```python
def add_audio(self, stream):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 用於添加音訊的串流。 |

## add_audio(self, audio_data) {#bytes}
從位元組陣列建立並添加音訊至簡報。

### 返回值
已添加的音訊。

```python
def add_audio(self, audio_data):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| audio_data | **bytes** | 音訊位元組。 |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
從串流建立並添加音訊至簡報。

### 返回值
已添加的音訊。

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 用於添加影片音訊的串流。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior) | 將套用於串流的行為。 |

### 另請參閱
* 類別 [`AudioCollection`](/slides/python-net/zh-hant/aspose.slides/audiocollection)
* 類別 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio)
* 列舉 [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)