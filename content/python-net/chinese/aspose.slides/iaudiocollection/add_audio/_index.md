---
title: add_audio method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
从另一个演示文稿添加音频文件的副本。

### 返回
已添加音频。

```python
def add_audio(self, audio):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio) | 源音频。 |

## add_audio(self, stream) {#iorawiobase}
从流中创建并将音频添加到演示文稿。

### 返回
已添加音频。

```python
def add_audio(self, stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 用于添加音频的流。 |

## add_audio(self, audio_data) {#bytes}
从字节数组创建并将音频添加到演示文稿。

### 返回
已添加音频。

```python
def add_audio(self, audio_data):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| audio_data | **bytes** | 音频字节。 |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
从流中创建并将音频添加到演示文稿。

### 返回
已添加音频。

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 用于添加视频音频的流。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/zh/aspose.slides/loadingstreambehavior) | 将应用于流的行为。 |

### 另请参见
* 类 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio)
* 类 [`IAudioCollection`](/slides/python-net/zh/aspose.slides/iaudiocollection)
* 枚举 [`LoadingStreamBehavior`](/slides/python-net/zh/aspose.slides/loadingstreambehavior)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)