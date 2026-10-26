---
title: Parallel
second_title: Aspose.Slides C++ API 参考
description: 提供对并行循环和区域的支持。
type: docs
weight: 1
url: /zh/system.threading.tasks/parallel/
---
## Parallel 类

Provides support for parallel loops and regions.

```cpp
class Parallel
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | 在 IEnumerable 上执行 foreach 操作，迭代可以并行运行。 |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | 在 IEnumerable 上执行 foreach 操作，迭代可以并行运行。 |
## 备注

此类提供用于循环和操作的并行执行方法。

## 另请参见

* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)