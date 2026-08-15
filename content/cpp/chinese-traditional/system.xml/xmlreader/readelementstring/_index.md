---
title: ReadElementString()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: "讀取僅含文字的元素。不過，建議改用 XmlReader::ReadElementContentAsString 方法，因為它提供了更直接的方式來處理此操作。"
type: docs
weight: 859
url: /zh-hant/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() 方法

讀取僅含文字的元素。不過，建議改用 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 方法，因為它提供了更直接的方式來處理此操作。

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### 傳回值

讀取的元素所包含的文字。如果元素為空，則回傳空字串。

## XmlReader::ReadElementString(String) 方法

在讀取僅含文字的元素之前，先檢查找到的元素的 [XmlReader::get_Name](../get_name/) 值是否與給定的字串相符。不過，建議改用 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 方法，因為它提供了更直接的方式來處理此操作。

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要檢查的名稱。 |

### 傳回值

讀取的元素所包含的文字。如果元素為空，則回傳空字串。

## XmlReader::ReadElementString(String, String) 方法

在讀取僅含文字的元素之前，先檢查找到的元素的 [XmlReader::get_LocalName](../get_localname/) 與 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值是否與給定的字串相符。不過，建議改用 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 方法，因為它提供了更直接的方式來處理此操作。

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 要檢查的本機名稱。 |
| ns | [String](../../../system/string/) | 要檢查的命名空間 URI。 |

### 傳回值

讀取的元素所包含的文字。如果元素為空，則回傳空字串。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)