---
title: RemoveAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 依名稱移除屬性。
type: docs
weight: 235
url: /zh-hant/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) 方法

依名稱移除屬性。

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要移除的屬性名稱。這是一個限定名稱。它會與匹配節點的 **get_Name** 值進行比對。 |

## XmlElement::RemoveAttribute(String, String) 方法

移除具有指定本地名稱和命名空間 URI 的屬性。（如果被移除的屬性具有預設值，則會立即以該預設值取代。）

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要移除的屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 要移除的屬性的命名空間 URI。 |

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlElement](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)