---
title: operator>>()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用 UTF-8 編碼從輸入串流取得字串。
type: docs
weight: 3004
url: /zh-hant/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) 函式

從輸入串流取得字串，使用 UTF-8 編碼。

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| in | std::istream\& | 一個輸入串流物件（**basic_ostream** 以 **char** 為模板實例化）。 |
| str | [String](../string/)\& | 從輸入串流讀取的字串。 |

### 返回值

一個已從中提取字串的輸入串流。

## System::operator>>(std::wistream\&, String\&) 函式

從輸入串流取得字串。

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| in | std::wistream\& | 一個輸入串流物件（**basic_ostream** 以 **wchar_t** 為模板實例化）。 |
| str | [String](../string/)\& | 從輸入串流讀取的字串。 |

### 返回值

一個已從中提取字串的輸入串流。

## 另見

* 類別 [String](../string/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)