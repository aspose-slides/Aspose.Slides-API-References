---
title: HasAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 判斷目前的節點是否具有指定名稱的屬性。
type: docs
weight: 300
url: /zh-hant/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) 方法


判斷目前的節點是否具有指定名稱的屬性。

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要搜尋的屬性名稱。這是一個限定名稱，會與符合節點的 **get_Name** 值進行比對。 |

### 回傳值

**true** 如果目前的節點具有指定的屬性；否則 **false**。

## XmlElement::HasAttribute(String, String) 方法


判斷目前的節點是否具有指定本機名稱與命名空間 URI 的屬性。

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要搜尋的屬性本機名稱。 |
| namespaceURI | [String](../../../system/string/) | 要搜尋的屬性命名空間 URI。 |

### 回傳值

**true** 如果目前的節點具有指定的屬性；否則 **false**。

## 相關參考

* 類別 [String](../../../system/string/)
* 類別 [XmlElement](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)