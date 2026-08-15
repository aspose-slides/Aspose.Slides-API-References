---
title: IsUpper()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定字串中指定索引處的字元是否被歸類為大寫字母。
type: docs
weight: 183
url: /zh-hant/system/char/isupper/
---
## Char::IsUpper(const String\&, int) 方法

判斷指定字串中指定索引處的字符是否被歸類為大寫字母。

```cpp
static bool System::Char::IsUpper(const String &str, int idx)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 包含字元的字串。 |
| idx | int | 在指定字串中要測試的零基索引。 |

### 返回值

如果指定索引處的字符是大寫字母則返回 true，否則返回 false。

## Char::IsUpper(const char_t *, int) 方法

判斷指定字元緩衝區中指定索引處的字符是否被歸類為大寫字母。

```cpp
static bool System::Char::IsUpper(const char_t *str, int idx)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區起始位置的指標。 |
| idx | int | 在指定緩衝區中要測試的字元的零基索引。 |

### 返回值

如果指定索引處的字符是大寫字母則返回 true，否則返回 false。

## Char::IsUpper(char_t) 方法

判斷指定的字符是否被歸類為大寫字母。

```cpp
static bool System::Char::IsUpper(char_t c)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要測試的字符。 |

### 返回值

如果指定的字符是大寫字母則返回 true，否則返回 false。

## 另請參閱

* 類別 [String](../../string/)
* 類別 [Char](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)