---
title: ReadAsync()
second_title: Aspose.Slides C++ API 参考
description: 异步读取当前流中的字节序列，按读取的字节数前移流中的位置，并监视取消请求。
type: docs
weight: 196
url: /zh/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) 方法

异步读取当前流中的字节序列，按读取的字节数前移流中的位置，并监视取消请求。

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用于写入读取字节的字节数组。 |
| offset | **int32_t** | 在 **buffer** 中的基于 0 的起始写入位置。 |
| count | **int32_t** | 要读取的字节数。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用于监视取消请求的令牌。 |

### 返回值

表示异步读取操作的任务。TResult 参数的值包含读取到 buffer 中的字节总数。如果当前可用的字节数少于请求的字节数，则结果值可能小于请求的字节数；如果已到达流的末尾，则结果值可能为 0（零）。

## 参见

* 类型别名 [RTaskPtr](../../../system/rtaskptr/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [CancellationToken](../../../system.threading/cancellationtoken/)
* 类 [FileStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)