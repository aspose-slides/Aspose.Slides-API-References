---
title: WriteAsync()
second_title: Aspose.Slides for C++ API 参考
description: 异步将一系列字节写入当前流，按写入的字节数推进此流中的当前位置，并监视取消请求。
type: docs
weight: 261
url: /zh/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) 方法

异步写入一系列字节到当前流中，按写入的字节数推进此流中的当前定位，并监视取消请求。

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入的字节的数组。 |
| offset | **int32_t** | 在 **buffer** 中子范围写入开始位置的基于0的索引。 |
| count | **int32_t** | 要写入的子范围中元素的数量。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用于监视取消请求的令牌。 |

### 返回值

表示异步写入操作的任务。

## 另见

* 类型定义 [TaskPtr](../../../system/taskptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [CancellationToken](../../../system.threading/cancellationtoken/)
* 类 [FileStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)