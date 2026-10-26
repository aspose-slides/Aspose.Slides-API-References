---
title: Parallel
second_title: Aspose.Slides for C++ API リファレンス
description: 並列ループと領域のサポートを提供します。
type: docs
weight: 1
url: /ja/system.threading.tasks/parallel/
---
## Parallel クラス

並列ループと領域のサポートを提供します。

```cpp
class Parallel
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | イテレーションが並列で実行できる IEnumerable に対して foreach 操作を実行します。 |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | イテレーションが並列で実行できる IEnumerable に対して foreach 操作を実行します。 |

## 備考

このクラスは、ループや操作の並列実行のためのメソッドを提供します。

## 参照

* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)