---
title: FindAll()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された述語によって定義された条件に一致するすべての要素を取得します。
type: docs
weight: 664
url: /ja/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) メソッド


指定された述語によって定義された条件に一致するすべての要素を取得します。

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) で要素を検索する |
| match | [System::Predicate](../../predicate/)\<T\> | 配列要素に対して条件を一致させるために定義された述語 |

### 戻り値

指定された述語によって定義された条件に一致するすべての要素を含む[Array](../)を返します。見つからない場合は、空の[Array](../)を返します。

## 関連項目

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)