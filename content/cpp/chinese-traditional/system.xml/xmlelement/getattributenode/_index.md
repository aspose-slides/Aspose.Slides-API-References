---
title: GetAttributeNode()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回具有指定名稱的 XmlAttribute。
type: docs
weight: 248
url: /zh-hant/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) 方法

傳回具有指定名稱的 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要擷取的屬性名稱。這是一個限定名稱。它會對照匹配節點的 **get_Name** 值。 |

### 回傳值

指定的 [XmlAttribute](../../xmlattribute/) 或 **nullptr**（若未找到匹配的屬性）。

## XmlElement::GetAttributeNode(String, String) 方法

傳回具有指定本機名稱和命名空間 URI 的 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本機名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 回傳值

指定的 [XmlAttribute](../../xmlattribute/) 或 **nullptr**（若未找到匹配的屬性）。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlAttribute](../../xmlattribute/)
* 類別 [String](../../../system/string/)
* 類別 [XmlElement](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)