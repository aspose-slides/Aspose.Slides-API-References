---
title: add_video method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
从另一个演示文稿中添加一个视频文件的副本。

### 返回
已添加的视频。

```python
def add_video(self, video):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/zh/aspose.slides/ivideo) | 源视频。 |

## add_video(self, video_data) {#bytes}
从字节数组创建并向演示文稿添加视频。

### 返回
已添加的视频。

```python
def add_video(self, video_data):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| video_data | **bytes** | 视频字节。 |

## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
从流创建并向演示文稿添加视频。

### 返回
已添加 [`IVideo`](/slides/python-net/zh/aspose.slides/ivideo)。

```python
def add_video(self, stream, loading_stream_behavior):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 用于添加视频文件的流。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/zh/aspose.slides/loadingstreambehavior) | 将应用于流的行为。 |

### 另见
* 类 [`IVideo`](/slides/python-net/zh/aspose.slides/ivideo)
* 类 [`IVideoCollection`](/slides/python-net/zh/aspose.slides/ivideocollection)
* 枚举 [`LoadingStreamBehavior`](/slides/python-net/zh/aspose.slides/loadingstreambehavior)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)