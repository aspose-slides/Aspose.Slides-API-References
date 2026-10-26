---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考
description: 傳回具有指定索引的屬性。
type: docs
weight: 1
url: /zh-hant/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) 方法


傳回具有指定索引的屬性。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | **int32_t** | 屬性的索引。 |

### 返回值

在指定索引處的屬性。

## XmlAttributeCollection::idx_get(const String\&) 方法


傳回具有指定名稱的屬性。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 屬性的限定名稱。 |

### 返回值

具有指定名稱的屬性。若屬性不存在，此方法傳回 **nullptr**。

## XmlAttributeCollection::idx_get(const String\&, const String\&) 方法


傳回具有指定本地名稱和命名空間統一資源識別碼 (URI) 的屬性。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 屬性的本地名稱。 |
| namespaceURI | const [String](../../../system/string/)\& | 屬性的命名空間 URI。 |

### 返回值

具有指定本地名稱和命名空間 URI 的屬性。若屬性不存在，此方法傳回 **nullptr**。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlAttribute](../../xmlattribute/)
* 類別 [XmlAttributeCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)