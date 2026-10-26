---
title: IsSurrogatePair()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷兩個指定的字元是否為 UTF-16 代理對。
type: docs
weight: 27
url: /zh-hant/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) 方法

判斷兩個指定的字元是否構成 UTF-16 代理對。

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | 測試是否為高位代理的字元 |
| lowSurrogate | char_t | 測試是否為低位代理的字元 |

### 傳回值

如果指定的字元構成代理對則傳回 true，否則傳回 false

## Char::IsSurrogatePair(const String\&, int) 方法

判斷指定字元緩衝區中的兩個連續字元是否構成代理對。

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | 字串 |
| index | int | 指定緩衝區中測試字元序列開始的零基索引 |

### 傳回值

如果指定的字元構成代理對則傳回 true，否則傳回 false

## 另請參閱

* 類別 [Char](../)
* 類別 [String](../../string/)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)