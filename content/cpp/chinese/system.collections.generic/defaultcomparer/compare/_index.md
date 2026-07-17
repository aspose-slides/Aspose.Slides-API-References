---
title: Compare()
second_title: Aspose.Slides C++ API 参考
description: 实际数据比较。
type: docs
weight: 1
url: /zh/system.collections.generic/defaultcomparer/compare/
---
## DefaultComparer::Compare(typename ThisType::args_type, typename ThisType::args_type) const 方法

实际数据比较。

```cpp
virtual int System::Collections::Generic::DefaultComparer<T, typename>::Compare(typename ThisType::args_type x, typename ThisType::args_type y) const override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | typename [ThisType::args_type](../../icomparer/args_type/) | 左操作数。 |
| y | typename [ThisType::args_type](../../icomparer/args_type/) | 右操作数。 |

### 返回值

如果 **x** 小于 **y**，则返回负值；如果操作数相等则返回 0；否则返回正值。

## 另见

* Typedef [args_type](../../icomparer/args_type/)
* Class [DefaultComparer](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)