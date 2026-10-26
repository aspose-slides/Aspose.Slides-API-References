---
title: insert_audio_frame_linked method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/insert_audio_frame_linked/
weight: 220
---
## insert_audio_frame_linked(self, index, x, y, width, height, fname) {#int-float-float-float-float-str}
创建一个链接到外部音频文件的新音频框架，并将其插入到指定索引处的形状集合中。

### 返回

新创建的[`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)。



```python
def insert_audio_frame_linked(self, index, x, y, width, height, fname):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入音频框架的零基索引。 |
| x | **float** | 新音频框架的 x 坐标，单位为点。 |
| y | **float** | 新音频框架的 y 坐标，单位为点。 |
| width | **float** | 新音频框架的宽度，单位为点。 |
| height | **float** | 新音频框架的高度，单位为点。 |
| fname | **str** | 要链接的外部音频文件的路径或名称。 |



### 参见
* 类 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)