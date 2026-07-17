---
title: FromCanceled()
second_title: Aspose.Slides C++ API 参考
description: 创建一个因指定令牌被取消而完成的任务。
type: docs
weight: 118
url: /zh/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) 函数

创建一个因指定令牌被取消而完成的任务。

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 导致任务被取消的取消令牌。 |

### 返回值

一个已取消的任务。

## 另见

* 类型定义 [TaskPtr](../../system/taskptr/)
* 类 [CancellationToken](../../system.threading/cancellationtoken/)
* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)