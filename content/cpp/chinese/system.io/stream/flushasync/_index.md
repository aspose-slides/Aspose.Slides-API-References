---
title: FlushAsync()
second_title: Aspose.Slides for C++ API 参考
description: 异步清除此流的所有缓冲区，使任何缓冲的数据写入底层设备，并监视取消请求。
type: docs
weight: 118
url: /zh/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) 方法

异步清除此流的所有缓冲区，使任何缓冲的数据写入底层设备，并监视取消请求。

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用于监视取消请求的令牌。 |

### 返回值

表示异步刷新操作的任务。

## Stream::FlushAsync() 方法

异步清除此流的所有缓冲区，使任何缓冲的数据写入底层设备，并监视取消请求。

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### 返回值

表示异步刷新操作的任务。

## 另请参见

* 类型定义 [TaskPtr](../../../system/taskptr/)
* 类 [CancellationToken](../../../system.threading/cancellationtoken/)
* 类 [Stream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)