---
title: ForEach()
second_title: Aspose.Slides for C++ API 参考
description: 在 IEnumerable 上执行 foreach 操作，迭代可以并行运行。
type: docs
weight: 1
url: /zh/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method

执行对 IEnumerable 的 foreach 操作，迭代可以并行运行。

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| TSource | The type of the data in the source. |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | 一个可枚举的数据源。 |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | 配置此操作行为的对象。 |
| body | const [Action](../../../system/action/)\<TSource\>\& | 在每次迭代中调用一次的委托。 |

### 返回值

一个 [ParallelLoopResult](../../parallelloopresult/) 结构，包含有关循环已完成部分的信息。

## 备注

此方法将源可枚举对象分区，并在多个线程上并发执行 body 委托。

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method

执行对 IEnumerable 的 foreach 操作，迭代可以并行运行。

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| TSource | The type of the data in the source. |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | 一个可枚举的数据源。 |
| body | const [Action](../../../system/action/)\<TSource\>\& | 在每次迭代中调用一次的委托。 |

### 返回值

一个 [ParallelLoopResult](../../parallelloopresult/) 结构，包含有关循环已完成部分的信息。

## 备注

使用默认的 [ParallelOptions](../../paralleloptions/)，具有无限的并行度且不支持取消。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [Action](../../../system/action/)
* 类 [ParallelLoopResult](../../parallelloopresult/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [ParallelOptions](../../paralleloptions/)
* 类 [Parallel](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)