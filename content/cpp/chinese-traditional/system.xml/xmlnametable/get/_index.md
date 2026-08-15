---
title: Get()
second_title: Aspose.Slides for C++ API 參考手冊
description: 在衍生類別中覆寫時，取得與給定陣列中指定字元範圍相同字元的原子化字串。
type: docs
weight: 1
url: /zh-hant/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法

在衍生類別中覆寫時，取得與指定陣列中給定字元範圍相同字元的原子化字串。

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 包含要查詢之名稱的字元陣列。 |
| offset | **int32_t** | 指定名稱第一個字元之、以零為基礎的陣列索引。 |
| length | **int32_t** | 名稱的字元數。 |

### 傳回值

原子化字串，若字串尚未被原子化則返回 **nullptr**。如果 **length** 為零，[String::Empty](../../../system/string/empty/) 被傳回。

## XmlNameTable::Get(const String\&) 方法

在衍生類別中覆寫時，取得與指定字串相同值的原子化字串。

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | 要查詢的名稱。 |

### 傳回值

原子化字串，若字串尚未被原子化則返回 **nullptr**。

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [XmlNameTable](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)