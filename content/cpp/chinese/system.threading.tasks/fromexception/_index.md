---
title: FromException()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个已完成且带有指定异常的任务。
type: docs
weight: 131
url: /zh/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) 函数

创建一个已完成且带有指定异常的任务。

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | 用于完成任务的异常。 |

### 返回值

一个已故障的任务。

## System::Threading::Tasks::FromException(const Exception\&) 函数

创建一个已完成且带有指定异常和结果类型的任务。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | 任务结果的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | 用于完成任务的异常。 |

### 返回值

一个具有指定结果类型的已故障任务。

## 另请参阅

* 类型定义 [TaskPtr](../../system/taskptr/)
* 类型定义 [Exception](../../system/exception/)
* 类型定义 [RTaskPtr](../../system/rtaskptr/)
* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)