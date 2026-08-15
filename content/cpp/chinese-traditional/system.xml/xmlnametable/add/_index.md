---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 在衍生類別中覆寫時，會將指定的字串原子化並加入至 XmlNameTable。
type: docs
weight: 14
url: /zh-hant/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法

When overridden in a derived class, atomizes the specified string and adds it to the [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 包含要加入之名稱的字元陣列。 |
| offset | **int32_t** | 以零為起點的索引，指向陣列中名稱的第一個字元。 |
| length | **int32_t** | 名稱的字元數。 |

### 返回值

若不存在則返回新的原子化字串，若已存在則返回現有的字串。 如果長度為零，將返回 [String::Empty](../../../system/string/empty/)。

## XmlNameTable::Add(const String\&) 方法

When overridden in a derived class, atomizes the specified string and adds it to the [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | 要加入的名稱。 |

### 返回值

若不存在則返回新的原子化字串，若已存在則返回現有的字串。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)