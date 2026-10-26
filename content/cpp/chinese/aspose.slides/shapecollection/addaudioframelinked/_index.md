---
title: AddAudioFrameLinked()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个链接到外部音频文件的新音频框，并将其添加到形状集合的末尾。
type: docs
weight: 261
url: /zh/aspose.slides/shapecollection/addaudioframelinked/
---
## ShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) method

创建一个链接到外部音频文件的新音频框，并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新音频框的 x 坐标，单位为点。 |
| y | **float** | 新音频框的 y 坐标，单位为点。 |
| width | **float** | 新音频框的宽度，单位为点。 |
| height | **float** | 新音频框的高度，单位为点。 |
| fname | [System::String](../../../system/string/) | 要链接的外部音频文件的路径或名称。 |

### 返回值

新创建的[IAudioFrame](../../iaudioframe/)。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)