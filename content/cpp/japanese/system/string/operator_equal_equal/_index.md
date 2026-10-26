---
title: operator==()
second_title: Aspose.Slides for C++ API リファレンス
description: 等価比較演算子。
type: docs
weight: 300
url: /ja/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const メソッド

等価比較演算子。

```cpp
bool System::String::operator==(const String &str) const
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) を現在のものと比較するために。 |

### 戻り値

両方の文字列が null であるか、両方が null でなく一致する場合は true、そうでない場合は false。

## String::operator==(std::nullptr_t) const メソッド

文字列が null かどうかを確認します。[IsNull()](../isnull/) 呼び出しと同じロジックを適用します。

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### 戻り値

文字列が null の場合は true、そうでない場合は false。

## 参照

* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)