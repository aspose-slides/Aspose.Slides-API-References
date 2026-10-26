---
title: IsSymbol()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷指定字元緩衝區中指定索引處的字元是否被分類為符號字元。
type: docs
weight: 144
url: /zh-hant/system/char/issymbol/
---
## Char::IsSymbol(const char_t *, int) method

判斷指定字符緩衝區中指定索引處的字符是否被分類為符號字符。

```cpp
static bool System::Char::IsSymbol(const char_t *str, int idx)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char_t * | 指向字符緩衝區起始位置的指標 |
| idx | int | 要測試的字符在指定緩衝區中的零基索引 |

### 回傳值

True if the character at the specified index is a symbol character, otherwise - false

## Char::IsSymbol(char_t) method

判斷指定的字符是否被分類為符號字符。

```cpp
static bool System::Char::IsSymbol(char_t c)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要測試的字符 |

### 回傳值

True if the specified character is a symbol character, otherwise - false

## 另請參閱

* 類別 [Char](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)