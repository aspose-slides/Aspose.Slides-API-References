---
title: TryGetBuffer()
second_title: Aspose.Slides for C++ API 参考
description: 返回用于创建此流的无符号字节数组。
type: docs
weight: 170
url: /zh/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) 方法


返回用于创建此流的无符号字节数组。

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | 字节数组 - 输出参数。当此方法返回 true 时，返回用于创建此流的字节数组片段；当此方法返回 false 时，此参数被设置为默认值。 |

### 返回值

如果转换成功则为 True。

## 另见

* 类 [ArraySegment](../../../system/arraysegment/)
* 类 [MemoryStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)