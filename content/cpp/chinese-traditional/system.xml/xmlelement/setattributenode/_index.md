---
title: SetAttributeNode()
second_title: Aspose.Slides for C++ API 參考
description: 新增指定的 XmlAttribute。
type: docs
weight: 261
url: /zh-hant/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) 方法


新增指定的 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | 要加入此元素的屬性集合的 [XmlAttribute](../../xmlattribute/) 節點。 |

### 返回值

如果屬性取代了具有相同名稱的現有屬性，則會返回舊的 [XmlAttribute](../../xmlattribute/)；否則，返回 **nullptr**。

## XmlElement::SetAttributeNode(String, String) 方法


新增指定的 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 返回值

要加入的 [XmlAttribute](../../xmlattribute/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlAttribute](../../xmlattribute/)
* 類別 [XmlElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)