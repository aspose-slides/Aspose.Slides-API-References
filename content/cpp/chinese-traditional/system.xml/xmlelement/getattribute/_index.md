---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回具有指定名稱之屬性的值。
type: docs
weight: 209
url: /zh-hant/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) 方法

傳回具有指定名稱的屬性的值。

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要擷取的屬性名稱。這是一個限定名稱。它會對應至匹配節點的 **get_Name** 值。 |

### 回傳值

指定屬性的值。如果找不到匹配的屬性，或該屬性沒有指定或預設值，則傳回空字串。

## XmlElement::GetAttribute(String, String) 方法

傳回具有指定本地名稱與命名空間 URI 的屬性的值。

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要擷取的屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 要擷取的屬性的命名空間 URI。 |

### 回傳值

指定屬性的值。如果找不到匹配的屬性，或該屬性沒有指定或預設值，則傳回空字串。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [XmlElement](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)