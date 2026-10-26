---
title: LINQ_First()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスの最初の要素を返します。
type: docs
weight: 53
url: /ja/system.collections.generic/ienumerable/linq_first/
---
## IEnumerable::LINQ_First() メソッド

シーケンスの最初の要素を返します。

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_First()
```

### 戻り値

シーケンスの最初の要素。

## IEnumerable::LINQ_First(const Func\<T, bool\>\&) メソッド

指定された条件を満たすシーケンスの最初の要素を返します。

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_First(const Func<T, bool> &predicate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| predicate | const [Func](../../../system/func/)\<T, **bool**\>\& | 各要素が条件を満たすかテストする関数。 |

### 戻り値

指定された条件を満たすシーケンスの最初の要素。

## 参照

* クラス [IEnumerable](../)
* クラス [Func](../../../system/func/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)