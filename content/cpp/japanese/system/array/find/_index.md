---
title: Find()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列内で、指定された述語の条件を満たす最初の要素を検索します。
type: docs
weight: 651
url: /ja/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) メソッド

指定された配列内で、指定された述語の条件を満たす最初の要素を検索します。

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) で検索対象となる配列 |
| match | [System::Predicate](../../predicate/)\<T\> | 配列要素に対して一致させる条件を定義する述語 |

### 戻り値

述語で定義された条件を満たす配列の最初の要素のコピー、条件を満たさない場合は型 T の既定値

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* 型定義 [Predicate](../../predicate/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)