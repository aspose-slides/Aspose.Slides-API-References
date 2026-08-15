---
title: CompareOrdinal()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用序數模式比較兩個字串，返回小於、等於或大於的結果。
type: docs
weight: 833
url: /zh-hant/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String&) 方法

使用序數模式比較兩個字串，返回小於、等於或大於的結果。

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比較的第一個字串。 |
| strB | const [String](../)\& | 要比較的第二個字串。 |

### 返回值

如果第一子字串小於第二子字串則返回負值，若相等則返回零，否則返回正值。

## String::CompareOrdinal(const String\&, int, const String\&, int, int) 方法

使用序數模式比較兩個字串，返回小於、等於或大於的結果。

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比較的第一個字串。 |
| indexA | int | 第一個字串子字串的起始位置。 |
| strB | const [String](../)\& | 要比較的第二個字串。 |
| indexB | int | 第二個字串子字串的起始位置。 |
| length | int | 要比較的字元數量。 |

### 返回值

如果第一子字串小於第二子字串則返回負值，若相等則返回零，否則返回正值。

## 另見

* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)