---
title: FindIndex()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列内で、指定された述語の条件を満たす最初の要素を検索します。
type: docs
weight: 638
url: /ja/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) メソッド

指定された配列内で、指定された述語の条件を満たす最初の要素を検索します。

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) で要素を検索する |
| match | [System::Predicate](../../predicate/)\<T\> | 配列要素と照合する条件を定義する述語 |

### 戻り値

配列内で述語によって定義された条件を満たす最初の要素のインデックス。それ以外の場合は -1

## 関連項目

* 型定義 [ArrayPtr](../../arrayptr/)
* 型定義 [Predicate](../../predicate/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)