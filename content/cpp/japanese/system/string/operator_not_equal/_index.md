---
title: operator!=()
second_title: Aspose.Slides for C++ API リファレンス
description: 等価でない比較演算子。
type: docs
weight: 313
url: /ja/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const method

等価でない比較演算子。

```cpp
bool System::String::operator!=(const String &str) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 現在のものと比較するための |

### 戻り値

false if both strings are null or both are not null and match, true otherwise.

## String::operator!=(std::nullptr_t) const method

文字列が null でないかを確認します。[IsNull()](../isnull/) 呼び出しと同じロジックを適用します。

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### 戻り値

false if string is null, true otherwise.

## 関連項目

* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)