---
title: operator|=()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を右側の引数として使用し、現在のオブジェクトが表す値に operator|=() を適用します。
type: docs
weight: 261
url: /ja/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) メソッド

Applies [operator|=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | The template parameter to make SFINAE work. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | **bool** | A boolean value that is used as a right-side value of the [operator|=()](./) applied to the value represented by the current object. |

### 戻り値

自身への参照。

## 関連項目

* クラス [Nullable](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)