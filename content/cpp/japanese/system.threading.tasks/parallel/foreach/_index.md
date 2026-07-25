---
title: ForEach()
second_title: Aspose.Slides for C++ API リファレンス
description: IEnumerable に対して foreach 操作を実行し、イテレーションが並列で実行される可能性があります。
type: docs
weight: 1
url: /ja/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) メソッド


IEnumerable に対して foreach 操作を実行します。この操作ではイテレーションが並列で実行される可能性があります。

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TSource | The type of the data in the source. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | An object that configures the behavior of this operation. |
| body | const [Action](../../../system/action/)\<TSource\>\& | The delegate that is invoked once per iteration. |

### 戻り値

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## 備考



このメソッドはソースの enumerable を分割し、body デリゲートを複数のスレッドで同時に実行します。 
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) メソッド


IEnumerable に対して foreach 操作を実行します。この操作ではイテレーションが並列で実行される可能性があります。

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TSource | The type of the data in the source. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| body | const [Action](../../../system/action/)\<TSource\>\& | The delegate that is invoked once per iteration. |

### 戻り値

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## 備考



デフォルトの [ParallelOptions](../../paralleloptions/) を使用し、無制限の並列性およびキャンセルなしで実行します。 
## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* クラス [ParallelLoopResult](../../parallelloopresult/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* クラス [ParallelOptions](../../paralleloptions/)
* クラス [Parallel](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)