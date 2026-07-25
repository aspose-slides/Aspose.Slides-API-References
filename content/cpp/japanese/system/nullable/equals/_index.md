---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す値が、指定された Nullable オブジェクトが表す値と等しいかどうかを判断します。
type: docs
weight: 131
url: /ja/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const メソッド

現在のオブジェクトが表す値が、指定された [Nullable](../) オブジェクトが表す値と等しいかどうかを判定します。

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 比較対象となる [Nullable](../) オブジェクトの基礎となる型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const T1\& | 比較対象となる [Nullable](../) オブジェクトへの定数参照 |

### 戻り値

現在のオブジェクトが表す値が、指定された [Nullable](../) オブジェクトが表す値と等しい場合は true、それ以外の場合は false

## 関連項目

* クラス [Nullable](../)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)