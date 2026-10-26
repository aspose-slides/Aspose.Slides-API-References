---
title: Replace()
second_title: Aspose.Slides for C++ API リファレンス
description: ビルダーを使用してサブ文字列を置換します。
type: docs
weight: 196
url: /ja/system.text/stringbuilder/replace/
---
## StringBuilder::Replace(const String\&, const String\&) メソッド

ビルダーを使用してサブ文字列を置換します。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) を置換します。 |
| newString | const [String](../../../system/string/)\& | 置換文字列。 |

### 戻り値

このポインタ。

## StringBuilder::Replace(const String\&, const String\&, int, int) メソッド

ビルダーの範囲を使用してサブ文字列を置換します。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString, int position, int count)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) を置換します。 |
| newString | const [String](../../../system/string/)\& | 置換文字列。 |
| position | int | ビルダーの置換範囲の開始位置。 |
| count | int | ビルダーの置換範囲の長さ。 |

### 戻り値

このポインタ。

## StringBuilder::Replace(char_t, char_t) メソッド

ビルダーを使用して文字を置換します。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| oldChar | char_t | 置換する文字。 |
| newChar | char_t | 置換後の文字。 |

### 戻り値

このポインタ。

## StringBuilder::Replace(char_t, char_t, int, int) メソッド

ビルダーの範囲を使用して文字を置換します。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar, int startIndex, int count)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| oldChar | char_t | 置換する文字。 |
| newChar | char_t | 置換後の文字。 |
| startIndex | int | ビルダーの置換範囲の開始位置。 |
| count | int | ビルダーの置換範囲の長さ。 |

### 戻り値

このポインタ。

## 参照

* クラス [StringBuilder](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)