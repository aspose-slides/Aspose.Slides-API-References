---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 參考文件
description: "當在衍生類別中覆寫時，取得具有指定 XmlReader::get_Name 值的屬性。"
type: docs
weight: 599
url: /zh-hant/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) 方法

當在衍生類別中覆寫時，取得具有指定 [XmlReader::get_Name](../get_name/) 值的屬性。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的限定名稱。 |

### 返回值

指定屬性的值。如果找不到屬性或其值為 [String::Empty](../../../system/string/empty/)，則返回 **nullptr**。

## XmlReader::GetAttribute(String, String) 方法

當在衍生類別中覆寫時，取得具有指定 [XmlReader::get_LocalName](../get_localname/) 與 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值的屬性。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的本機名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的名稱空間 URI。 |

### 返回值

指定屬性的值。如果找不到屬性或其值為 [String::Empty](../../../system/string/empty/)，則返回 **nullptr**。此方法不會移動讀取器。

## XmlReader::GetAttribute(int32_t) 方法

當在衍生類別中覆寫時，取得具有指定索引的屬性。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | **int32_t** | 屬性的索引。索引從 0 起算。（第一個屬性的索引為 0。） |

### 返回值

指定屬性的值。此方法不會移動讀取器。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)