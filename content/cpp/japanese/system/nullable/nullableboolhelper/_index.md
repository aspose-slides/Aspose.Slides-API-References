---
title: NullableBoolHelper()
second_title: Aspose.Slides for C++ API リファレンス
description: このオブジェクトと other が両方とも null でないかを確認し、そうであればラムダを呼び出すヘルパー関数です。implementation.s で使用されます。
type: docs
weight: 105
url: /ja/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

Helper function to check if this and **other** are both not nulls and call a lambda if so. Used in implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| T1 | 他の nullable 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | 比較対象となる他の nullable 値。 |
| f | const std::function\<**bool**()>\& | 両方の **this** と **other** が null でない場合に呼び出すラムダ。 |
| default_if_both_are_null | **bool** | 両方の値が null の場合の戻り値。 |

### 戻り値

false if either **this** or **other** is null; **default_if_both_are_null** if both are null; result of **f** call if both are not null.

## 関連項目

* クラス [Nullable](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)