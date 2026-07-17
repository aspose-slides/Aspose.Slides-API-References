---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: 将字节复制到指定的流。
type: docs
weight: 209
url: /zh/system.io/stream/copyto/
---
## Stream::CopyTo(const SharedPtr\<Stream\>\&) 方法

复制字节到指定的流。

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) 要复制数据的目标。 |

## Stream::CopyTo(const SharedPtr\<Stream\>\&, int32_t) 方法

复制字节到指定的流，使用指定的缓冲区大小。

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination, int32_t buffer_size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) 要复制数据的目标。 |
| buffer_size | **int32_t** | 缓冲区的大小。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)