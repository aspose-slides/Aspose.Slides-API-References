---
title: LINQ_All()
second_title: Aspose.Slides の C++ API リファレンス
description: シーケンスのすべての要素が条件を満たすかどうかを判断します。
type: docs
weight: 144
url: /ja/system.collections.generic/ienumerable/linq_all/
---
## IEnumerable::LINQ_All(std::function\<bool(T)>) メソッド

シーケンスのすべての要素が条件を満たすかどうかを判断します。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_All(std::function<bool(T)> predicate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 各要素が条件を満たすかテストする関数。 |

### 戻り値

指定された predicate でテストに合格したソースシーケンスのすべての要素がある場合、またはシーケンスが空の場合は true、そうでなければ false。

## 参照

* クラス [IEnumerable](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)