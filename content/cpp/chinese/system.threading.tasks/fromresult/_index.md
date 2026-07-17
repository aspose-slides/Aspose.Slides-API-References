---
title: FromResult()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个已成功完成且具有指定结果的任务。
type: docs
weight: 144
url: /zh/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult(TResult) 函数

创建一个已成功完成且具有指定结果的任务。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | 任务结果的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| result | TResult | 用于完成任务的结果值。 |

### 返回值

一个成功完成的任务。

## 参见

* 类型定义 [RTaskPtr](../../system/rtaskptr/)
* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)