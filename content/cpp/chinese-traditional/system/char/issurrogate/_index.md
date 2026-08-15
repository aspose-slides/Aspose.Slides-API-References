---
title: IsSurrogate()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定的字元是否為 UTF-16 替代碼元。
type: docs
weight: 14
url: /zh-hant/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) 方法


Determines if the specified character is a UTF-16 surrogate code unit.

```cpp
static bool System::Char::IsSurrogate(char_t c)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | 字元 |

### 傳回值

如果指定字元是 UTF-16 替代碼元則為 True，否則為 false

## Char::IsSurrogate(const String\&, int) 方法


Determines whether the character at the specified index in the specified string is UTF-16 surrogate code unit.

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 字串 |
| index | int | 指定字串中字元的索引 |

### 傳回值

如果指定字元是 UTF-16 替代碼元則為 True，否則為 false

## 參見

* 類別 [Char](../)
* 類別 [String](../../string/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)