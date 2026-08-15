---
title: IsHighSurrogate()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷指定字串中指定索引處的字元是否為 UTF-16 高位代理組代碼單元。
type: docs
weight: 40
url: /zh-hant/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) 方法

判斷指定字串中指定索引處的字元是否為 UTF-16 高位代理組代碼單元。

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 字串 |
| index | int | 指定字串中要測試的字元索引 |

### 傳回值

若指定索引處的字元為 UTF-16 高位代理組代碼單元則回傳 true，否則回傳 false

## Char::IsHighSurrogate(const char_t *, int) 方法

判斷指定字元緩衝區中指定索引處的字元是否為高位代理。

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區開頭的指標 |
| idx | int | 指定緩衝區中要測試的字元的零基索引 |

### 傳回值

若指定索引處的字元為高位代理則回傳 true，否則回傳 false

## Char::IsHighSurrogate(char_t) 方法

判斷指定的字元是否為高位代理。

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 傳回值

若指定的字元為高位代理則回傳 true，否則回傳 false

## 參見

* 類別 [String](../../string/)
* 類別 [Char](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)