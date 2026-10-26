---
title: InsertVideoFrame()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新的视频帧并将其插入到指定索引的形状集合中。
type: docs
weight: 183
url: /zh/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) 方法

创建一个新的视频帧并将其插入到指定索引的形状集合中。

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入视频帧的零基索引。 |
| x | **float** | 新视频帧的 x 坐标，单位为点。 |
| y | **float** | 新视频帧的 y 坐标，单位为点。 |
| width | **float** | 新视频帧的宽度，单位为点。 |
| height | **float** | 新视频帧的高度，单位为点。 |
| fname | [System::String](../../../system/string/) | 要嵌入的视频文件的路径或名称。 |

### 返回值

新创建的[IVideoFrame](../../ivideoframe/)。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IVideoFrame](../../ivideoframe/)
* 类 [String](../../../system/string/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)