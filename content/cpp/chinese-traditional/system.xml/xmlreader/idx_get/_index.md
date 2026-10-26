---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中覆寫時，取得具有指定索引的屬性值。
type: docs
weight: 612
url: /zh-hant/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) 方法

當在衍生類別中覆寫時，取得具有指定索引的屬性值。

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | **int32_t** | 屬性的索引。 |

### 傳回值

指定屬性的值。

## XmlReader::idx_get(String) 方法

當在衍生類別中覆寫時，取得具有指定 [XmlReader::get_Name](../get_name/) 值的屬性值。

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的限定名稱。 |

### 傳回值

指定屬性的值。若未找到該屬性，則回傳 **nullptr**。

## XmlReader::idx_get(String, String) 方法

當在衍生類別中覆寫時，取得具有指定 [XmlReader::get_LocalName](../get_localname/) 與 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值的屬性值。

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的本機名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 傳回值

指定屬性的值。若未找到該屬性，則回傳 **nullptr**。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)