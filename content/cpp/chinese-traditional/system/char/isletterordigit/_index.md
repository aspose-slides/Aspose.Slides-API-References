---
title: IsLetterOrDigit()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定字元緩衝區中指定索引處的字元是否被歸類為 Unicode 字母或十進位數字。
type: docs
weight: 105
url: /zh-hant/system/char/isletterordigit/
---
## Char::IsLetterOrDigit(const char_t *, int) 方法


判斷指定字元緩衝區中指定索引處的字元是否被歸類為 Unicode 字母或十進位數字。

```cpp
static bool System::Char::IsLetterOrDigit(const char_t *str, int idx)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區起始位置的指標 |
| idx | int | 在指定緩衝區中要測試之字元的零基索引 |

### 回傳值

若指定索引處的字元是 Unicode 字母或十進位數字，則傳回 True，否則傳回 false。

## Char::IsLetterOrDigit(char_t) 方法


判斷指定的字元是否被歸類為 Unicode 字母或十進位數字。

```cpp
static bool System::Char::IsLetterOrDigit(char_t c)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 回傳值

若指定的字元是 Unicode 字母或十進位數字，則傳回 True，否則傳回 false。

## 另請參閱

* 類別 [Char](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)