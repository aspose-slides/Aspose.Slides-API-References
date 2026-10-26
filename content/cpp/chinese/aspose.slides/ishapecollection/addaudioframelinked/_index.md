---
title: AddAudioFrameLinked()
second_title: Aspose.Slides C++ API 参考
description: 创建一个链接到外部音频文件的新音频帧，并将其添加到形状集合的末端。
type: docs
weight: 222
url: /zh/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) 方法

创建一个链接到外部音频文件的新音频帧，并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新音频帧的 x 坐标，单位为点。 |
| y | **float** | 新音频帧的 y 坐标，单位为点。 |
| width | **float** | 新音频帧的宽度，单位为点。 |
| height | **float** | 新音频帧的高度，单位为点。 |
| fname | [System::String](../../../system/string/) | 要链接的外部音频文件的路径或名称。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAudioFrame](../../iaudioframe/)
* 类 [String](../../../system/string/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)