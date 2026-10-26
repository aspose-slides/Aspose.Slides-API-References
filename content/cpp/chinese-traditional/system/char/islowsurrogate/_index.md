---
title: IsLowSurrogate()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定字元緩衝區中指定索引處的字元是否為低位代理項。
type: docs
weight: 53
url: /zh-hant/system/char/islowsurrogate/
---
## Char::IsLowSurrogate(const char_t *, int) 方法

判斷指定字元緩衝區中指定索引處的字元是否為低位代理項。

```cpp
static bool System::Char::IsLowSurrogate(const char_t *str, int idx)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | const char_t * | 指向字元緩衝區開頭的指標 |
| idx | int | 指定緩衝區中要測試的字元之零基索引 |

### 返回值

如果指定索引處的字元是低位代理項，則返回 True；否則返回 false

## Char::IsLowSurrogate(char_t) 方法

判斷指定的字元是否為低位代理項。

```cpp
static bool System::Char::IsLowSurrogate(char_t c)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| c | char_t | 要測試的字元 |

### 返回值

如果指定的字元是低位代理項，則返回 True；否則返回 false

## 另請參閱

* 類別 [Char](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)