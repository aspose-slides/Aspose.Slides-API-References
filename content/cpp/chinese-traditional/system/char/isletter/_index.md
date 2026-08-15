---
title: IsLetter()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷指定字元緩衝區中指定索引處的字元是否被歸類為 Unicode 字母。
type: docs
weight: 92
url: /zh-hant/system/char/isletter/
---
## Char::IsLetter(const char_t *, int) 方法


判斷指定字元緩衝區中指定索引處的字元是否被歸類為 Unicode 字母。

```cpp
static bool System::Char::IsLetter(const char_t *str, int idx)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區開始位置的指標 |
| idx | int | 在指定緩衝區中要測試的字元的零基索引 |

### 傳回值

如果指定索引處的字元是 Unicode 字母，則返回 true；否則返回 false

## Char::IsLetter(char_t) 方法


判斷指定字元是否被歸類為 Unicode 字母。

```cpp
static bool System::Char::IsLetter(char_t c)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 傳回值

如果指定字元是 Unicode 字母，則返回 true；否則返回 false

## 另請參閱

* 類別 [Char](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)