---
title: Add()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的字串原子化並加入到 NameTable。
type: docs
weight: 14
url: /zh-hant/system.xml/nametable/add/
---
## NameTable::Add(const String\&) 方法

將指定的字串原子化並加入到 [NameTable](../)。

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | 要加入的字串。 |

### 返回值

原子化的字串，或如果已存在於 [NameTable](../) 則返回現有的字串。

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法

將指定的字串原子化並加入到 [NameTable](../)。

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 包含要加入之字串的字元陣列。 |
| start | **int32_t** | 指向陣列中字串第一個字元的零基索引。 |
| len | **int32_t** | 字串中的字元數。 |

### 返回值

原子化的字串，或如果已存在於 [NameTable](../) 則返回現有的字串。若 **len** 為零，則返回 [String::Empty](../../../system/string/empty/)。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [NameTable](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)