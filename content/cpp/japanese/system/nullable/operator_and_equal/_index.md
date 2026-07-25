---
title: operator&=()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を右側引数として使用し、現在のオブジェクトが表す値に operator&=() を適用します。
type: docs
weight: 274
url: /ja/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) メソッド


指定された値を右側引数として使用し、現在のオブジェクトが表す値に [operator&=()](./) を適用します。

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | SFINAE を機能させるためのテンプレート パラメータです。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | **bool** | 現在のオブジェクトが表す値に適用される [operator&=()](./) の右側値として使用されるブール値です。 |

### 戻り値

自身への参照。

## 参照

* クラス [Nullable](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)