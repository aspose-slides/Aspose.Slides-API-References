---
title: Replace()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列内の文字のすべての出現箇所を置換します。
type: docs
weight: 742
url: /ja/system/string/replace/
---
## String::Replace(char_t, char_t) const メソッド

文字列内の文字のすべての出現箇所を置換します。

```cpp
String System::String::Replace(char_t oldValue, char_t newValue) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oldValue | char_t | 置換対象の文字。 |
| newValue | char_t | 置換後の値。 |

### 戻り値

[String](../) 置換が完了した。

## String::Replace(const String\&, const String\&) const メソッド

この文字列内で検索文字列のすべての出現箇所を置換します。

```cpp
String System::String::Replace(const String &oldValue, const String &newValue) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oldValue | const [String](../)\& | [String](../) を置換対象。 |
| newValue | const [String](../)\& | 置換文字列。 |

### 戻り値

[String](../) 置換が完了した。

## 関連項目

* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)