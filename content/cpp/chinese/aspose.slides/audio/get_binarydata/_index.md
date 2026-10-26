---
title: get_BinaryData()
second_title: Aspose.Slides 用于 C++ 的 API 参考
description: "返回音频数据的副本。 当数据量较大时，建议使用 Audio::GetStream 方法，以防止不必要地将音频数据加载到内存中，甚至导致 OutOfMemoryException。 只读 uint8_t[]."
type: docs
weight: 27
url: /zh/aspose.slides/audio/get_binarydata/
---
## Audio::get_BinaryData() 方法

返回音频数据的副本。 在数据量大的情况下，建议使用 [Audio::GetStream](../getstream/) 方法，以避免不必要地将音频数据加载到内存中，甚至导致 OutOfMemoryException。 只读 **uint8_t**[].

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Audio::get_BinaryData() override
```

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Audio](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)