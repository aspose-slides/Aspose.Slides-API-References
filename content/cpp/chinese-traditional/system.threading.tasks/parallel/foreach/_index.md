---
title: ForEach()
second_title: Aspose.Slides for C++ API 參考
description: 在 IEnumerable 上執行 foreach 操作，迭代可以平行執行。
type: docs
weight: 1
url: /zh-hant/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) 方法

對 IEnumerable 執行 foreach 操作，迭代可以平行執行。

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| TSource | 來源中資料的類型。 |

### 引數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | 可列舉的資料來源。 |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | 用於設定此操作行為的物件。 |
| body | const [Action](../../../system/action/)\<TSource\>\& | 在每次迭代時呼叫一次的委派。 |

### 傳回值

[ParallelLoopResult](../../parallelloopresult/) 結構，包含已完成迴圈部分的資訊。

## 備註

此方法將來源可列舉物件分割，並在多執行緒上同時執行 body 委派。

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) 方法

對 IEnumerable 執行 foreach 操作，迭代可以平行執行。

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| TSource | 來源中資料的類型。 |

### 引數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | 可列舉的資料來源。 |
| body | const [Action](../../../system/action/)\<TSource\>\& | 在每次迭代時呼叫一次的委派。 |

### 傳回值

[ParallelLoopResult](../../parallelloopresult/) 結構，包含已完成迴圈部分的資訊。

## 備註

使用預設的 [ParallelOptions](../../paralleloptions/)，具無限平行度且不支援取消。

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [Action](../../../system/action/)
* 類別 [ParallelLoopResult](../../parallelloopresult/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [ParallelOptions](../../paralleloptions/)
* 類別 [Parallel](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)