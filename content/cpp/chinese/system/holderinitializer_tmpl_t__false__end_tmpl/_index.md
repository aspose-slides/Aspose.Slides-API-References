---
title: HolderInitializer< T, false >
second_title: Aspose.Slides C++ API 参考
description: HolderInitializer 特化用于 T 为值类型的情况。使用上下文允许返回对临时对象的引用，因为保证实例将被调用方复制。因此，此特化仅用作桩，什么也不做。
type: docs
weight: 1626
url: /zh/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct


[HolderInitializer](../holderinitializer/) 对于 T 为值类型的情况的特化。使用环境允许返回对临时对象的引用，因为保证实例会被调用方复制。因此，此特化仅用作桩，什么也不做。

```cpp
template<typename T>class HolderInitializer< T, false >
```

## Methods

| 方法 | 描述 |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |
## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)