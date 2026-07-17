---
title: get_BinaryData()
second_title: Aspose.Slides for C++ API 参考
description: "返回音频数据的副本。如果数据量很大，考虑使用 IAudio::GetStream 方法，以防止不必要地将音频数据加载到内存中，甚至导致 OutOfMemoryException。只读 uint8_t[]."
type: docs
weight: 14
url: /zh/aspose.slides/iaudio/get_binarydata/
---
## IAudio::get_BinaryData() 方法


返回音频数据的副本。如果数据量很大，考虑使用 [IAudio::GetStream](../getstream/) 方法以防止不必要地将音频数据加载到内存中，甚至导致 OutOfMemoryException。只读 **uint8_t**[].

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IAudio::get_BinaryData()=0
```

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IAudio](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)