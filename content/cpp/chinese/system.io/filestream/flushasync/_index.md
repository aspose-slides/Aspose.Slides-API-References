---
title: FlushAsync()
second_title: Aspose.Slides C++ API 参考
description: 异步清除此流的所有缓冲区，使任何缓冲的数据写入底层设备，并监视取消请求。
type: docs
weight: 157
url: /zh/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) 方法

异步清除此流的所有缓冲区，使任何缓冲的数据写入底层设备，并监视取消请求。

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用于监视取消请求的令牌。 |

### 返回值

表示异步刷新操作的任务。

## 参见

* Typedef [TaskPtr](../../../system/taskptr/)
* 类 [CancellationToken](../../../system.threading/cancellationtoken/)
* 类 [FileStream](../)
* 命名空间 [System::IO](../../)
* Library [Aspose.Slides](../../../)