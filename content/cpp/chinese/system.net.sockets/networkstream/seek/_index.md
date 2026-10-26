---
title: Seek()
second_title: Aspose.Slides C++ API 参考
description: 设置当前对象所表示的流的位置。
type: docs
weight: 183
url: /zh/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(int64_t, IO::SeekOrigin) 方法


Sets the position of the stream represented by the current object.

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offset | **int64_t** | The byte offset relative to a position specified by **origin** |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | Specifies the position from which and the direction toward which the offset is calculated |

### 返回值

The new position of the stream

## 另见

* 枚举 [SeekOrigin](../../../system.io/seekorigin/)
* 类 [NetworkStream](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)