---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个链接到外部音频文件的新音频帧，并将其插入到指定索引的形状集合中。
type: docs
weight: 274
url: /zh/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) 方法

创建一个链接到外部音频文件的新音频帧，并将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入音频帧的零基索引。 |
| x | **float** | 新音频帧的 x 坐标，单位为点。 |
| y | **float** | 新音频帧的 y 坐标，单位为点。 |
| width | **float** | 新音频帧的宽度，单位为点。 |
| height | **float** | 新音频帧的高度，单位为点。 |
| fname | [System::String](../../../system/string/) | 要链接的外部音频文件的路径或名称。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)