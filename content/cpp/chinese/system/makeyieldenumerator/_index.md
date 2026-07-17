---
title: MakeYieldEnumerator()
second_title: Aspose.Slides for C++ API 参考
description: 从 yield 函数创建 IEnumerator。
type: docs
weight: 2393
url: /zh/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) 函数

从 yield 函数创建 IEnumerator。

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
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

指向 IEnumerator 的共享指针

## 另请参见

* 类型定义 [SharedPtr](../sharedptr/)
* 类 [IEnumerator](../../system.collections.generic/ienumerator/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)