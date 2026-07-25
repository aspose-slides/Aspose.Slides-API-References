---
title: LINQ_Any()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスに要素が含まれているかどうかを判断します。
type: docs
weight: 157
url: /ja/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() メソッド

シーケンスに要素が含まれているかどうかを判断します。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```

### 戻り値

ソースシーケンスに要素が含まれている場合は true、そうでない場合は false。

## IEnumerable::LINQ_Any(std::function\<bool(T)>) メソッド

シーケンスの任意の要素が存在するか、条件を満たすかどうかを判断します。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 各要素が条件を満たすかテストする関数。 |

### 戻り値

ソースシーケンスに要素が含まれている場合は true、そうでない場合は false。

## 参照

* クラス [IEnumerable](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)