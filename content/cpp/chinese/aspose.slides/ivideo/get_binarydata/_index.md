---
title: get_BinaryData()
second_title: Aspose.Slides C++ API 参考
description: "返回音频数据的副本。 若数据量很大，建议使用 IVideo::GetStream 方法，以防止不必要地将视频数据加载到内存中，甚至导致 OutOfMemoryException。 只读 uint8_t[]."
type: docs
weight: 14
url: /zh/aspose.slides/ivideo/get_binarydata/
---
## IVideo::get_BinaryData() 方法

返回音频数据的副本。 如果数据量很大，考虑使用 [IVideo::GetStream](../getstream/) 方法，以防止不必要地将视频数据加载到内存中，甚至导致 OutOfMemoryException。 只读 **uint8_t**[]。

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IVideo::get_BinaryData()=0
```

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IVideo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)