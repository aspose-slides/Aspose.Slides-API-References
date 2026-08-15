---
title: IsWhiteSpace()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定字元緩衝區中指定索引處的字元是否被歸類為空白字元。
type: docs
weight: 157
url: /zh-hant/system/char/iswhitespace/
---
## Char::IsWhiteSpace(const char_t *, int) 方法

判斷指定字元緩衝區中指定索引處的字元是否被歸類為空白字元。

```cpp
static bool System::Char::IsWhiteSpace(const char_t *str, int idx)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區起始位置的指標 |
| idx | int | 在指定緩衝區中要測試之字元的零基索引 |

### 回傳值

如果指定索引處的字元是空白字元，則返回 True，否則返回 false

## Char::IsWhiteSpace(char_t) 方法

判斷指定的字元是否被歸類為空白字元。

```cpp
static bool System::Char::IsWhiteSpace(char_t c)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 回傳值

如果指定的字元是空白字元，則返回 True，否則返回 false

## Char::IsWhiteSpace(const String\&, int) 方法

判斷指定字串中指定索引處的字元是否被歸類為空白字元。

```cpp
static bool System::Char::IsWhiteSpace(const String &str, int index)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 字串 |
| index | int | 在指定字串中的零基索引 |

### 回傳值

如果指定索引處的字元是空白字元，則返回 True，否則返回 false

## 相關參考

* 類別 [Char](../)
* 類別 [String](../../string/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)