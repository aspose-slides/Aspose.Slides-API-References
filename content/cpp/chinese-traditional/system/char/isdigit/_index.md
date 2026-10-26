---
title: IsDigit()
second_title: Aspose.Slides for C++ API 參考手冊
description: 判斷指定字元緩衝區中指定索引處的字元是否被歸類為十進位數字。
type: docs
weight: 79
url: /zh-hant/system/char/isdigit/
---
## Char::IsDigit(const char_t *, int) 方法


判斷指定字元緩衝區中指定索引處的字元是否被歸類為十進位數字。

```cpp
static bool System::Char::IsDigit(const char_t *str, int idx)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區起始位置的指標 |
| idx | int | 要測試的字元在指定緩衝區中的零基索引 |

### 回傳值

如果指定索引處的字元是十進位數字則回傳 True，否則回傳 false

## Char::IsDigit(const String\&, const int32_t) 方法


判斷指定字串中指定索引處的字元是否被歸類為十進位數字。

```cpp
static bool System::Char::IsDigit(const String &str, const int32_t idx)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 一個字串 |
| idx | const **int32_t** | 要測試的字元在指定緩衝區中的零基索引 |

### 回傳值

如果指定索引處的字元是十進位數字則回傳 True，否則回傳 false

## Char::IsDigit(char_t) 方法


判斷指定的字元是否被歸類為十進位數字。

```cpp
static bool System::Char::IsDigit(char_t c)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 回傳值

如果指定的字元是十進位數字則回傳 True，否則回傳 false

## 參見

* 類別 [Char](../)
* 類別 [String](../../string/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)