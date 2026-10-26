---
title: IsSeparator()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷指定字元緩衝區中指定索引處的字元是否被分類為分隔字元。
type: docs
weight: 131
url: /zh-hant/system/char/isseparator/
---
## Char::IsSeparator(const char_t *, int) 方法

判斷指定字元緩衝區中指定索引處的字元是否被分類為分隔字元。

```cpp
static bool System::Char::IsSeparator(const char_t *str, int idx)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區開頭的指標 |
| idx | int | 要測試的字元在指定緩衝區中的零基索引 |

### 返回值

如果指定索引處的字元是分隔字元則返回 true，否則返回 false

## Char::IsSeparator(char_t) 方法

判斷指定的字元是否被分類為分隔字元。

```cpp
static bool System::Char::IsSeparator(char_t c)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 返回值

如果指定的字元是分隔字元則返回 true，否則返回 false

## 另請參閱

* 類別 [Char](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)