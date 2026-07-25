---
title: LINQ_Count()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンス内の要素数を返します（直接カウントにより計算）。
type: docs
weight: 118
url: /ja/system.collections.generic/ienumerable/linq_count/
---
## IEnumerable::LINQ_Count() メソッド

シーケンス内の要素数を返します（直接カウントにより計算）。

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count()
```

### 戻り値

シーケンス内の要素数。

## IEnumerable::LINQ_Count(const Func\<T, bool\>\&) メソッド

指定された条件を満たすシーケンス内の要素数を返します。

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count(const Func<T, bool> &predicate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| predicate | const [Func](../../../system/func/)\<T, **bool**\>\& | 各要素が条件を満たすかテストする関数。 |

### 戻り値

指定された条件を満たすシーケンス内の要素数。

## 参照

* クラス [IEnumerable](../)
* クラス [Func](../../../system/func/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)