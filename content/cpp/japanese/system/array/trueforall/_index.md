---
title: TrueForAll()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列のすべての要素が、指定された述語によって定義された条件を満たすかどうかを判断します。
type: docs
weight: 677
url: /ja/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) メソッド

指定された配列のすべての要素が、指定された述語によって定義された条件を満たすかどうかを判断します。

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 条件に一致させる要素 |
| match | [System::Predicate](../../predicate/)\<T\> | 配列要素に一致させる条件を定義する述語 |

### 戻り値

配列 arr のすべての要素が述語 match によって定義された条件を満たす場合は true、それ以外の場合は false

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)