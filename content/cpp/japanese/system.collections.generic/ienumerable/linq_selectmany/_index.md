---
title: LINQ_SelectMany()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスの各要素を投影し、結果のシーケンスを 1 つのシーケンスに結合します。
type: docs
weight: 300
url: /ja/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) メソッド

シーケンスの各要素を投影し、結果のシーケンスを 1 つのシーケンスに結合します。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| ResultType | **selector** が返す値の型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | 変換関数。 |

### 戻り値

[IEnumerable](../) で、入力シーケンスの各要素に対して 1 対多の射影関数を呼び出した結果が含まれます。

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) メソッド

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)