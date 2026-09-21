---
title: add_audio method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
從另一個簡報新增音訊檔案的副本。

### Returns

已加入的音訊。

```python
def add_audio(self, audio):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio) | 來源音訊。 |

## add_audio(self, stream) {#iorawiobase}
從資料流建立並加入音訊至簡報。

### Returns

已加入的音訊。

```python
def add_audio(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | 要加入音訊的資料流。 |

## add_audio(self, audio_data) {#bytes}
從位元組陣列建立並加入音訊至簡報。

### Returns

已加入的音訊。

```python
def add_audio(self, audio_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| audio_data | **bytes** | 音訊位元組。 |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
從資料流建立並加入音訊至簡報。

### Returns

已加入的音訊。

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | 要加入影片音訊的資料流。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior) | 將套用於資料流的行為。 |

### See Also
* 類別 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio)
* 類別 [`IAudioCollection`](/slides/python-net/zh-hant/aspose.slides/iaudiocollection)
* 列舉 [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)