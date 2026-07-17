---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的视频帧并将其添加到形状集合的末尾。
type: docs
weight: 209
url: /zh/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) method

创建一个新的视频帧并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新视频帧的 x 坐标（单位为点）。 |
| y | **float** | 新视频帧的 y 坐标（单位为点）。 |
| width | **float** | 新视频帧的宽度（单位为点）。 |
| height | **float** | 新视频帧的高度（单位为点）。 |
| fname | [System::String](../../../system/string/) | 要嵌入的视频文件的路径或名称。 |

### 返回值

新创建的 [IVideoFrame](../../ivideoframe/)。

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) method

创建一个新的视频帧并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新视频帧的 x 坐标（单位为点）。 |
| y | **float** | 新视频帧的 y 坐标（单位为点）。 |
| width | **float** | 新视频帧的宽度（单位为点）。 |
| height | **float** | 新视频帧的高度（单位为点）。 |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 要嵌入视频帧的 [IVideo](../../ivideo/)。 |

### 返回值

新创建的 [IVideoFrame](../../ivideoframe/)。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Class [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)