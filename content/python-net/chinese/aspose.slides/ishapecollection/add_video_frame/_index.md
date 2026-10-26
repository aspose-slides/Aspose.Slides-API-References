---
title: add_video_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/add_video_frame/
weight: 160
---
## add_video_frame(self, x, y, width, height, fname) {#float-float-float-float-str}
创建一个新的视频帧并将其添加到形状集合的末尾。

### 返回

新创建的 [`IVideoFrame`](/slides/python-net/zh/aspose.slides/ivideoframe)。

```python
def add_video_frame(self, x, y, width, height, fname):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新视频帧的 x 坐标，单位为点。 |
| y | **float** | 新视频帧的 y 坐标，单位为点。 |
| width | **float** | 新视频帧的宽度，单位为点。 |
| height | **float** | 新视频帧的高度，单位为点。 |
| fname | **str** | 要嵌入的视频文件的路径或名称。 |

## add_video_frame(self, x, y, width, height, video) {#float-float-float-float-ivideo}
创建一个新的视频帧并将其添加到形状集合的末尾。

### 返回

新创建的 [`IVideoFrame`](/slides/python-net/zh/aspose.slides/ivideoframe)。

```python
def add_video_frame(self, x, y, width, height, video):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新视频帧的 x 坐标，单位为点。 |
| y | **float** | 新视频帧的 y 坐标，单位为点。 |
| width | **float** | 新视频帧的宽度，单位为点。 |
| height | **float** | 新视频帧的高度，单位为点。 |
| video | [`IVideo`](/slides/python-net/zh/aspose.slides/ivideo) | 要嵌入视频帧的 [`IVideo`](/slides/python-net/zh/aspose.slides/ivideo)。 |

### 另请参见
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 类 [`IVideo`](/slides/python-net/zh/aspose.slides/ivideo)
* 类 [`IVideoFrame`](/slides/python-net/zh/aspose.slides/ivideoframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)