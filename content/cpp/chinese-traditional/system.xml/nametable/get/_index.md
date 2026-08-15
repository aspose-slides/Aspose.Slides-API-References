---
title: Get()
second_title: Aspose.Slides for C++ API 參考
description: 返回具有指定值的已原子化字串。
type: docs
weight: 27
url: /zh-hant/system.xml/nametable/get/
---
## NameTable::Get(const String\&) 方法

返回具有指定值的已原子化字串。

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要尋找的名稱。 |

### 返回值

已原子化的字串物件；如果字串尚未被原子化，則返回 **nullptr**。

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法

返回包含給定陣列中指定字符範圍相同字符的已原子化字串。

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 包含要尋找之名稱的字符陣列。 |
| start | **int32_t** | 指定名稱第一個字符的基於零的陣列索引。 |
| len | **int32_t** | 名稱中的字符數。 |

### 返回值

已原子化的字串；如果字串尚未被原子化，則返回 **nullptr**。如果 **len** 為零，則返回 [String::Empty](../../../system/string/empty/)。

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [NameTable](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)