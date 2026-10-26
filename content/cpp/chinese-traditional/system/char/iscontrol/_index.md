---
title: IsControl()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定字元緩衝區中指定索引處的字元是否被分類為 Unicode 控制字元。
type: docs
weight: 66
url: /zh-hant/system/char/iscontrol/
---
## Char::IsControl(const char_t *, int) 方法

判斷指定字元緩衝區中指定索引處的字元是否被分類為 Unicode 控制字元。

```cpp
static bool System::Char::IsControl(const char_t *str, int idx)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區起始位置的指標 |
| idx | int | 指定緩衝區中要測試的字元的零基索引 |

### 返回值

若指定索引處的字元是 Unicode 控制字元則返回 True，否則返回 false

## Char::IsControl(char_t) 方法

判斷指定的字元是否被分類為 Unicode 控制字元。

```cpp
static bool System::Char::IsControl(char_t c)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 返回值

若指定的字元是 Unicode 控制字元則返回 True，否則返回 false

## 參見

* 類別 [Char](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)