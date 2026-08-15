---
title: Parallel
second_title: Aspose.Slides for C++ API 參考
description: 提供對平行迴圈和區域的支援。
type: docs
weight: 1
url: /zh-hant/system.threading.tasks/parallel/
---
## Parallel 類別


提供對平行迴圈和區域的支援。

```cpp
class Parallel
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | 對 IEnumerable 執行 foreach 作業，迭代可能以平行方式執行。 |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | 對 IEnumerable 執行 foreach 作業，迭代可能以平行方式執行。 |
## 備註


此類別提供用於平行執行迴圈和作業的方法。 
## 另見

* 命名空間 [System::Threading::Tasks](../)
* 函式庫 [Aspose.Slides](../../)