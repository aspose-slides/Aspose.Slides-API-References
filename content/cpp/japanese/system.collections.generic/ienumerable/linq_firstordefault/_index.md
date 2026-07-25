---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスの最初の要素を返し、シーケンスが空の場合はデフォルト値を返します。
type: docs
weight: 66
url: /ja/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() method

シーケンスの最初の要素を返します。シーケンスが空の場合は既定値を返します。

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### 戻り値

シーケンスの最初の要素、またはシーケンスが空の場合はデフォルト構築された値です。

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) method

条件を満たすシーケンスの最初の要素を返します。該当する要素が見つからない場合は既定値を返します。

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 各要素が条件を満たすかテストする関数です。 |

### 戻り値

source が空の場合、または predicate で指定されたテストに合格する要素がない場合は default(T) を返します。それ以外の場合、predicate で指定されたテストに合格する source の最初の要素を返します。

## 参照

* クラス [IEnumerable](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)