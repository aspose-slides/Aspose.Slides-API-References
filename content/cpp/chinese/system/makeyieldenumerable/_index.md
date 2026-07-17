---
title: MakeYieldEnumerable()
second_title: Aspose.Slides for C++ API 参考
description: 从 yield 函数创建 IEnumerable。
type: docs
weight: 2380
url: /zh/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&)函数

从 yield 函数创建 IEnumerable。

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 序列中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | 要执行的 yield 函数 |

### 返回值

指向 IEnumerable 的共享指针

## 另请参见

* 类型定义 [SharedPtr](../sharedptr/)
* 类 [IEnumerable](../../system.collections.generic/ienumerable/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)