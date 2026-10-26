---
title: IsPunctuation()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定字符緩衝區中指定索引處的字元是否被歸類為標點字元。
type: docs
weight: 209
url: /zh-hant/system/char/ispunctuation/
---
## Char::IsPunctuation(const char_t *, int) 方法

判斷指定字符緩衝區中指定索引處的字元是否被歸類為標點字元。

```cpp
static bool System::Char::IsPunctuation(const char_t *str, int idx)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char_t * | 指向字符緩衝區起始位置的指標 |
| idx | int | 在指定緩衝區中要測試的字元的零基索引 |

### 傳回值

如果指定索引處的字元是標點字元則回傳 true，否則回傳 false

## Char::IsPunctuation(char_t) 方法

判斷指定字元是否被歸類為標點字元。

```cpp
static bool System::Char::IsPunctuation(char_t c)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 傳回值

如果指定字元是標點字元則回傳 true，否則回傳 false

## 另請參閱

* 類別 [Char](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)