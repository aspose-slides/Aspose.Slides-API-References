---
title: Seek()
second_title: Aspose.Slides for C++ API 参考
description: 设置当前对象表示的流的位置。
type: docs
weight: 79
url: /zh/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) 方法

设置由当前对象表示的流的位置。

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offset | **int64_t** | The byte offset relative to a position specified by **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specifies the position from which and the direction toward which the offset is calculated |

### 返回值

The new position of the stream

## 另见

* 枚举 [SeekOrigin](../../seekorigin/)
* 类 [Stream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)