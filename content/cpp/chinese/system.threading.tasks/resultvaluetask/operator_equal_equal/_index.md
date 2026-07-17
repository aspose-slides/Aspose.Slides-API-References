---
title: operator==()
second_title: Aspose.Slides for C++ API 参考
description: ResultValueTask 的相等运算符。
type: docs
weight: 131
url: /zh/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const 方法

用于[ResultValueTask](../)的相等运算符。

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | 要与此实例比较的另一个[ResultValueTask](../)。 |

### 返回值

bool 如果两个任务具有相同的结果值或引用相同的底层任务，则为 True；否则为 false。

## 备注

如果任一实例包含直接结果值，则直接比较结果。否则，比较底层任务指针。

## 另见

* 类 [ResultValueTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)